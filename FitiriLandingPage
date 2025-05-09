import React, { useEffect, useState } from "react";

export default function HomePage() {
  const [showTopBtn, setShowTopBtn] = useState(false);

  useEffect(() => {
    const handleScroll = () => {
      setShowTopBtn(window.scrollY > 300);
    };
    window.addEventListener("scroll", handleScroll);
    return () => window.removeEventListener("scroll", handleScroll);
  }, []);

  const scrollToTop = () => {
    window.scrollTo({ top: 0, behavior: "smooth" });
  };

  return (
    <div className="min-h-screen bg-gray-50 text-gray-900 relative scroll-smooth">
      {/* Fixed Header */}
      <header className="fixed top-0 left-0 right-0 z-50 flex items-center justify-between p-6 shadow-md bg-white">
        <h1 className="text-2xl font-bold">Fitiri</h1>
        <nav className="space-x-6">
          <a href="#home" className="hover:text-blue-600">Home</a>
          <a href="#solutions" className="hover:text-blue-600">Solutions</a>
          <a href="#industries" className="hover:text-blue-600">Industries</a>
          <a href="#products" className="hover:text-blue-600">Products</a>
          <a href="#case-studies" className="hover:text-blue-600">Case Studies</a>
          <a href="#about" className="hover:text-blue-600">About</a>
          <a href="#contact" className="hover:text-blue-600">Contact</a>
          <a href="#schedule-demo" className="hover:text-blue-600">Schedule a Demo</a>
        </nav>
      </header>

      {/* Spacer for Fixed Header */}
      <div className="h-24"></div>

      {/* Hero Section */}
      <section id="home" className="text-center py-20 bg-gradient-to-r from-blue-100 to-white scroll-mt-24">
        <h2 className="text-4xl font-bold mb-4">Smarter Software for Critical Industries</h2>
        <p className="text-lg mb-6">Digital solutions built for reliability, safety, and performance in Oil & Gas and Fertilizer Manufacturing.</p>
        <div className="space-x-4">
          <a href="#solutions" className="px-6 py-2 bg-blue-600 text-white rounded-2xl hover:bg-blue-700 inline-block">View Our Solutions</a>
          <a href="#schedule-demo" className="px-6 py-2 bg-white border border-blue-600 text-blue-600 rounded-2xl hover:bg-blue-100 inline-block">Schedule a Demo</a>
        </div>
      </section>

      {/* Industries */}
      <section id="industries" className="py-16 px-6 scroll-mt-24">
        <h3 className="text-2xl font-semibold mb-8 text-center">Industries We Serve</h3>
        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
          <div className="bg-white p-4 rounded-xl shadow-md">
            <h4 className="font-bold text-lg mb-2">🛢️ Oil & Gas</h4>
            <p>Solutions for upstream, midstream, and downstream operations, including monitoring, safety compliance, and predictive analytics.</p>
          </div>
          <div className="bg-white p-4 rounded-xl shadow-md">
            <h4 className="font-bold text-lg mb-2">🌿 Fertilizer Manufacturing</h4>
            <p>Advanced automation and control systems, emission tracking, and energy management tailored for fertilizer production plants.</p>
          </div>
          <div className="bg-white p-4 rounded-xl shadow-md">
            <h4 className="font-bold text-lg mb-2">🧪 Petrochemicals</h4>
            <p>Real-time data acquisition and intelligent analytics to enhance product yield, process safety, and quality assurance.</p>
          </div>
          <div className="bg-white p-4 rounded-xl shadow-md">
            <h4 className="font-bold text-lg mb-2">🏭 Heavy Industry</h4>
            <p>End-to-end digital transformation solutions for energy efficiency, machine learning applications, and workforce safety.</p>
          </div>
        </div>
      </section>

      {/* Solutions */}
      <section id="solutions" className="bg-white py-16 px-6 scroll-mt-24">
        <h3 className="text-2xl font-semibold mb-8 text-center">Our Solutions</h3>
        <div className="grid md:grid-cols-2 gap-12">
          <div>
            <h4 className="text-xl font-bold mb-2">Oil & Gas</h4>
            <ul className="list-disc list-inside space-y-2">
              <li>Pipeline SCADA Systems</li>
              <li>Leak Detection & Alarm Management</li>
              <li>Production Optimization with AI</li>
              <li>Compliance and Regulatory Reporting</li>
              <li>Remote Asset Monitoring</li>
            </ul>
          </div>
          <div>
            <h4 className="text-xl font-bold mb-2">Fertilizer Manufacturing</h4>
            <ul className="list-disc list-inside space-y-2">
              <li>Batch Process Control</li>
              <li>Inventory & Supply Chain Visibility</li>
              <li>Digital Twin Models for Plant Simulation</li>
              <li>Environmental Emission Tracking</li>
              <li>Production Scheduling & Downtime Analysis</li>
            </ul>
          </div>
        </div>
      </section>

      {/* Products */}
      <section id="products" className="py-16 px-6 scroll-mt-24">
        <h3 className="text-2xl font-semibold mb-8 text-center">Products</h3>
        <div className="grid md:grid-cols-2 gap-12">
          <div className="bg-gray-100 p-6 rounded-xl shadow">
            <h4 className="text-xl font-bold mb-2">Fitiri Vision</h4>
            <p>Computer vision system for real-time equipment inspection, emissions monitoring, and process safety auditing.</p>
          </div>
          <div className="bg-gray-100 p-6 rounded-xl shadow">
            <h4 className="text-xl font-bold mb-2">Fitiri Flow</h4>
            <p>AI-powered process control optimization software that increases efficiency and minimizes unplanned downtime.</p>
          </div>
        </div>
      </section>

      {/* Case Studies */}
      <section id="case-studies" className="py-16 px-6 scroll-mt-24 bg-white">
        <h3 className="text-2xl font-semibold mb-8 text-center">Case Studies</h3>
        <div className="grid gap-8 md:grid-cols-2">
          <div className="border p-4 rounded-xl shadow">
            <h4 className="font-bold text-lg mb-2">Oil Platform Optimization</h4>
            <p>Reduced operational costs by 20% using Fitiri Flow's predictive analytics for equipment wear and performance trends.</p>
          </div>
          <div className="border p-4 rounded-xl shadow">
            <h4 className="font-bold text-lg mb-2">Green Fertilizer Initiative</h4>
            <p>Enabled a 30% cut in emissions through our digital twin model and precision emission tracking system.</p>
          </div>
        </div>
      </section>

{/* Client Testimonials */}
<section id="testimonials" className="bg-gray-50 py-16 px-6 text-center">
  <h3 className="text-2xl font-semibold mb-8">What Our Clients Say</h3>
  <div className="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
    <div className="bg-white p-6 rounded-2xl shadow-md">
      <p className="italic mb-4">“Fitiri's solutions completely transformed our pipeline monitoring. The real-time insights and alerts are game-changers.”</p>
      <p className="font-semibold">— Mark R., Operations Manager, GulfFlow Energy</p>
    </div>
    <div className="bg-white p-6 rounded-2xl shadow-md">
      <p className="italic mb-4">“The digital twin models Fitiri implemented saved us weeks of manual calibration. Brilliant work!”</p>
      <p className="font-semibold">— Priya D., Plant Engineer, GreenFert Corp</p>
    </div>
    <div className="bg-white p-6 rounded-2xl shadow-md">
      <p className="italic mb-4">“Their predictive analytics reduced our unplanned downtime by over 25%. Highly recommend their team.”</p>
      <p className="font-semibold">— Carlos M., Maintenance Lead, PetroNova</p>
    </div>
  </div>
</section>


      {/* About */}
      <section id="about" className="py-16 px-6 scroll-mt-24">
        <h3 className="text-2xl font-semibold mb-8 text-center">About Fitiri</h3>
        <p className="max-w-3xl mx-auto text-center">Fitiri is a leading provider of intelligent software solutions tailored to mission-critical industries. We bring decades of domain expertise, deep technical capabilities, and a relentless focus on customer outcomes.</p>
      </section>

      {/* Contact */}
      <section id="contact" className="py-16 px-6 bg-white scroll-mt-24">
        <h3 className="text-2xl font-semibold mb-8 text-center">Contact Us</h3>
        <form className="max-w-xl mx-auto space-y-4">
          <input type="text" placeholder="Name" className="w-full border p-3 rounded-xl" />
          <input type="email" placeholder="Email" className="w-full border p-3 rounded-xl" />
          <textarea placeholder="Message" rows="4" className="w-full border p-3 rounded-xl"></textarea>
          <button type="submit" className="w-full bg-blue-600 text-white py-3 rounded-xl hover:bg-blue-700">Send Message</button>
        </form>
      </section>

      {/* Schedule Demo */}
      <section id="schedule-demo" className="py-16 px-6 scroll-mt-24">
        <h3 className="text-2xl font-semibold mb-8 text-center">Schedule a Demo</h3>
        <form className="max-w-xl mx-auto space-y-4">
          <input type="text" placeholder="Full Name" className="w-full border p-3 rounded-xl" />
          <input type="email" placeholder="Email Address" className="w-full border p-3 rounded-xl" />
          <input type="text" placeholder="Company Name" className="w-full border p-3 rounded-xl" />
          <input type="text" placeholder="Industry" className="w-full border p-3 rounded-xl" />
          <textarea placeholder="Describe your needs" rows="4" className="w-full border p-3 rounded-xl"></textarea>
          <button type="submit" className="w-full bg-green-600 text-white py-3 rounded-xl hover:bg-green-700">Book Demo</button>
        </form>
      </section>

      {/* Back to Top Button */}
      {showTopBtn && (
        <button
          onClick={scrollToTop}
          className="fixed bottom-6 right-6 bg-blue-600 text-white p-3 rounded-full shadow-lg hover:bg-blue-700"
          aria-label="Scroll to top"
        >
          ↑
        </button>
      )}
    </div>
  );
}
