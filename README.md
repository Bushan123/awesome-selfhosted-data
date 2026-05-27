export default function WebvisionBusinessSolutions() {
  return (
    <div className="min-h-screen bg-slate-950 text-white overflow-hidden font-sans">
      {/* Background Effects */}
      <div className="absolute inset-0 bg-[radial-gradient(circle_at_top_right,rgba(59,130,246,0.25),transparent_35%)]"></div>
      <div className="absolute inset-0 bg-[radial-gradient(circle_at_bottom_left,rgba(37,99,235,0.20),transparent_35%)]"></div>

      {/* Navbar */}
      <header className="sticky top-0 z-50 backdrop-blur-xl bg-slate-950/70 border-b border-white/10">
        <div className="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
          <div>
            <h1 className="text-3xl font-black tracking-wide text-white">
              Webvision
            </h1>
            <p className="text-sm text-blue-300">Business Solutions</p>
          </div>

          <nav className="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
            <a href="#" className="hover:text-white transition">Home</a>
            <a href="#" className="hover:text-white transition">About</a>
            <a href="#" className="hover:text-white transition">Services</a>
            <a href="#" className="hover:text-white transition">Contact</a>
          </nav>

          <button className="bg-blue-600 hover:bg-blue-500 transition px-6 py-3 rounded-2xl font-semibold shadow-2xl shadow-blue-500/30">
            Get Consultation
          </button>
        </div>
      </header>

      {/* Hero Section */}
      <section className="relative px-6 py-28">
        <div className="max-w-7xl mx-auto grid lg:grid-cols-2 gap-16 items-center">
          <div>
            <div className="inline-flex items-center gap-2 bg-blue-500/10 border border-blue-400/20 text-blue-300 px-5 py-2 rounded-full mb-8 text-sm font-medium">
              Modern Telecalling Solutions
            </div>

            <h2 className="text-6xl lg:text-7xl font-black leading-tight mb-8">
              Corporate Communication
              <span className="block text-blue-400">That Drives Results</span>
            </h2>

            <p className="text-slate-300 text-lg leading-relaxed max-w-xl mb-10">
              Webvision Business Solutions delivers premium telecalling,
              customer support, collections, and lead generation services for
              modern businesses with professional voice communication systems.
            </p>

            <div className="flex flex-wrap gap-5">
              <button className="bg-blue-600 hover:bg-blue-500 transition px-8 py-4 rounded-2xl font-bold text-lg shadow-2xl shadow-blue-500/30">
                Start Project
              </button>

              <button className="border border-white/20 hover:bg-white hover:text-slate-900 transition px-8 py-4 rounded-2xl font-semibold text-lg backdrop-blur-xl">
                Explore Services
              </button>
            </div>

            <div className="grid grid-cols-3 gap-6 mt-14">
              <div>
                <h3 className="text-4xl font-black text-blue-400">24/7</h3>
                <p className="text-slate-400 mt-2">Customer Support</p>
              </div>

              <div>
                <h3 className="text-4xl font-black text-blue-400">100%</h3>
                <p className="text-slate-400 mt-2">Professional Service</p>
              </div>

              <div>
                <h3 className="text-4xl font-black text-blue-400">Fast</h3>
                <p className="text-slate-400 mt-2">Response System</p>
              </div>
            </div>
          </div>

          {/* Glassmorphism Card */}
          <div className="relative">
            <div className="absolute inset-0 bg-blue-500 blur-3xl opacity-20 rounded-full"></div>

            <div className="relative bg-white/10 border border-white/10 backdrop-blur-2xl rounded-[40px] p-10 shadow-2xl">
              <div className="space-y-6">
                <div className="bg-slate-900/60 rounded-3xl p-6 border border-white/10">
                  <div className="flex items-center justify-between mb-4">
                    <h3 className="text-2xl font-bold">Voice Process</h3>
                    <div className="w-4 h-4 bg-green-400 rounded-full animate-pulse"></div>
                  </div>
                  <p className="text-slate-300 leading-relaxed">
                    Advanced inbound and outbound telecalling solutions for business growth.
                  </p>
                </div>

                <div className="bg-slate-900/60 rounded-3xl p-6 border border-white/10">
                  <div className="flex items-center justify-between mb-4">
                    <h3 className="text-2xl font-bold">Lead Generation</h3>
                    <div className="w-4 h-4 bg-blue-400 rounded-full animate-pulse"></div>
                  </div>
                  <p className="text-slate-300 leading-relaxed">
                    Smart client acquisition strategies to maximize conversions.
                  </p>
                </div>

                <div className="bg-slate-900/60 rounded-3xl p-6 border border-white/10">
                  <div className="flex items-center justify-between mb-4">
                    <h3 className="text-2xl font-bold">Collections</h3>
                    <div className="w-4 h-4 bg-cyan-400 rounded-full animate-pulse"></div>
                  </div>
                  <p className="text-slate-300 leading-relaxed">
                    Professional collection services with effective follow-up systems.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Services */}
      <section className="relative py-28 px-6">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-20">
            <p className="text-blue-400 uppercase tracking-[0.3em] font-semibold mb-4">
              Our Expertise
            </p>
            <h2 className="text-5xl font-black mb-6">
              Modern Corporate Services
            </h2>
            <p className="text-slate-400 text-lg max-w-3xl mx-auto">
              Delivering professional communication services designed for modern businesses.
            </p>
          </div>

          <div className="grid lg:grid-cols-3 gap-8">
            <div className="group bg-white/5 hover:bg-blue-600 transition-all duration-500 rounded-[32px] p-10 border border-white/10 hover:-translate-y-2">
              <div className="w-16 h-16 rounded-2xl bg-blue-500/20 flex items-center justify-center text-3xl mb-8">
                📞
              </div>
              <h3 className="text-3xl font-bold mb-5">Telecalling</h3>
              <p className="text-slate-300 leading-relaxed text-lg">
                Professional voice support and customer communication services.
              </p>
            </div>

            <div className="group bg-white/5 hover:bg-blue-600 transition-all duration-500 rounded-[32px] p-10 border border-white/10 hover:-translate-y-2">
              <div className="w-16 h-16 rounded-2xl bg-blue-500/20 flex items-center justify-center text-3xl mb-8">
                📈
              </div>
              <h3 className="text-3xl font-bold mb-5">Lead Generation</h3>
              <p className="text-slate-300 leading-relaxed text-lg">
                Generate quality business leads and improve client engagement.
              </p>
            </div>

            <div className="group bg-white/5 hover:bg-blue-600 transition-all duration-500 rounded-[32px] p-10 border border-white/10 hover:-translate-y-2">
              <div className="w-16 h-16 rounded-2xl bg-blue-500/20 flex items-center justify-center text-3xl mb-8">
                💼
              </div>
              <h3 className="text-3xl font-bold mb-5">Collection Services</h3>
              <p className="text-slate-300 leading-relaxed text-lg">
                Structured payment follow-ups and collection management systems.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Contact CTA */}
      <section className="px-6 pb-24">
        <div className="max-w-6xl mx-auto bg-gradient-to-r from-blue-700 to-blue-500 rounded-[40px] p-14 shadow-2xl shadow-blue-500/30">
          <div className="grid lg:grid-cols-2 gap-10 items-center">
            <div>
              <p className="uppercase tracking-[0.25em] text-blue-100 font-semibold mb-4">
                Contact Us
              </p>
              <h2 className="text-5xl font-black leading-tight mb-6">
                Ready To Grow Your Business?
              </h2>
              <p className="text-blue-100 text-lg leading-relaxed">
                Partner with Webvision Business Solutions for premium telecalling and customer communication services.
              </p>
            </div>

            <div className="bg-white text-slate-900 rounded-[32px] p-10 shadow-2xl">
              <h3 className="text-3xl font-black mb-6">Business Contact</h3>

              <div className="space-y-5 text-lg">
                <div className="flex items-center gap-4">
                  <span className="text-2xl">📞</span>
                  <span className="font-semibold">+91 9502310749</span>
                </div>

                <div className="flex items-center gap-4">
                  <span className="text-2xl">🌐</span>
                  <span>Corporate Telecalling Services</span>
                </div>

                <div className="flex items-center gap-4">
                  <span className="text-2xl">🏢</span>
                  <span>Professional Business Solutions</span>
                </div>
              </div>

              <button className="w-full mt-8 bg-blue-600 hover:bg-blue-500 transition text-white py-4 rounded-2xl font-bold text-lg shadow-lg">
                Connect Now
              </button>

              <a
                href="https://wa.me/919502310749"
                target="_blank"
                rel="noopener noreferrer"
                className="w-full mt-4 flex items-center justify-center bg-green-500 hover:bg-green-400 transition text-white py-4 rounded-2xl font-bold text-lg shadow-lg"
              >
                WhatsApp Chat
              </a>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="border-t border-white/10 py-10 text-center text-slate-500">
        <p>© 2026 Webvision Business Solutions. All Rights Reserved.</p>
      </footer>

      {/* Floating WhatsApp Button */}
      <a
        href="https://wa.me/919502310749"
        target="_blank"
        rel="noopener noreferrer"
        className="fixed bottom-6 right-6 bg-green-500 hover:bg-green-400 transition w-16 h-16 rounded-full flex items-center justify-center text-3xl shadow-2xl z-50"
      >
        💬
      </a>

      {/* Admin Dashboard Preview */}
      <section className="py-24 px-6 bg-slate-900 border-t border-white/10">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-16">
            <p className="uppercase tracking-[0.25em] text-blue-400 font-semibold mb-4">
              Admin Panel
            </p>
            <h2 className="text-5xl font-black mb-6">
              Smart Business Dashboard
            </h2>
            <p className="text-slate-400 text-lg max-w-3xl mx-auto">
              Manage telecalling operations, employee performance, leads, and collections from one centralized dashboard.
            </p>
          </div>

          <div className="grid lg:grid-cols-4 gap-6 mb-10">
            <div className="bg-white/5 border border-white/10 rounded-3xl p-8">
              <p className="text-slate-400 mb-3">Total Calls</p>
              <h3 className="text-4xl font-black text-blue-400">12.5K</h3>
            </div>

            <div className="bg-white/5 border border-white/10 rounded-3xl p-8">
              <p className="text-slate-400 mb-3">Active Agents</p>
              <h3 className="text-4xl font-black text-blue-400">48</h3>
            </div>

            <div className="bg-white/5 border border-white/10 rounded-3xl p-8">
              <p className="text-slate-400 mb-3">Collections</p>
              <h3 className="text-4xl font-black text-blue-400">₹8.2L</h3>
            </div>

            <div className="bg-white/5 border border-white/10 rounded-3xl p-8">
              <p className="text-slate-400 mb-3">Customer Leads</p>
              <h3 className="text-4xl font-black text-blue-400">3.4K</h3>
            </div>
          </div>

          <div className="grid lg:grid-cols-2 gap-8">
            <div className="bg-white/5 border border-white/10 rounded-[32px] p-10">
              <h3 className="text-3xl font-bold mb-8">Employee Performance</h3>

              <div className="space-y-6">
                <div>
                  <div className="flex justify-between mb-2">
                    <span>Voice Process</span>
                    <span>92%</span>
                  </div>
                  <div className="w-full bg-slate-800 rounded-full h-3">
                    <div className="bg-blue-500 h-3 rounded-full w-[92%]"></div>
                  </div>
                </div>

                <div>
                  <div className="flex justify-between mb-2">
                    <span>Lead Conversion</span>
                    <span>80%</span>
                  </div>
                  <div className="w-full bg-slate-800 rounded-full h-3">
                    <div className="bg-cyan-500 h-3 rounded-full w-[80%]"></div>
                  </div>
                </div>

                <div>
                  <div className="flex justify-between mb-2">
                    <span>Collection Success</span>
                    <span>88%</span>
                  </div>
                  <div className="w-full bg-slate-800 rounded-full h-3">
                    <div className="bg-green-500 h-3 rounded-full w-[88%]"></div>
                  </div>
                </div>
              </div>
            </div>

            <div className="bg-white/5 border border-white/10 rounded-[32px] p-10">
              <h3 className="text-3xl font-bold mb-8">Hosting & Security</h3>

              <div className="space-y-5 text-slate-300 text-lg">
                <div className="flex items-center gap-4">
                  <span>☁️</span>
                  <span>Cloud Hosting Ready</span>
                </div>

                <div className="flex items-center gap-4">
                  <span>🔒</span>
                  <span>SSL Secure Website</span>
                </div>

                <div className="flex items-center gap-4">
                  <span>⚡</span>
                  <span>Fast Performance Optimization</span>
                </div>

                <div className="flex items-center gap-4">
                  <span>📱</span>
                  <span>Mobile Responsive Design</span>
                </div>

                <div className="flex items-center gap-4">
                  <span>🌐</span>
                  <span>Custom Domain Integration</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  );
}