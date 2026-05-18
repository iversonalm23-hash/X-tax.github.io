 X-tax.github.io
export default function XTaxLearningWebsite() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-blue-50 to-white text-gray-800">
      {/* Hero Section */}
      <header className="bg-blue-700 text-white py-16 px-6 text-center shadow-lg">
        <h1 className="text-5xl font-bold mb-4">X Tax</h1>
        <p className="text-xl max-w-3xl mx-auto">
          Learn how taxes work, why they matter, and how easy it can be to file taxes online.
        </p>
        <button className="mt-8 bg-white text-blue-700 px-6 py-3 rounded-2xl font-semibold shadow hover:scale-105 transition">
          Start Learning Today
        </button>
      </header>

      {/* What Are Taxes */}
      <section className="max-w-6xl mx-auto py-16 px-6 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h2 className="text-3xl font-bold mb-4">What Are Taxes?</h2>
          <p className="text-lg leading-relaxed">
            Taxes are money people and businesses pay to help support important public services.
            Governments use taxes to pay for schools, hospitals, roads, parks, police, firefighters,
            transportation, and programs that help communities grow stronger.
          </p>
        </div>
        <div className="bg-blue-100 p-8 rounded-3xl shadow-md">
          <h3 className="text-2xl font-semibold mb-3">Why Taxes Matter</h3>
          <ul className="space-y-3 text-lg list-disc list-inside">
            <li>Support public schools and education</li>
            <li>Help maintain roads and transportation</li>
            <li>Fund hospitals and healthcare programs</li>
            <li>Provide services for seniors and families</li>
          </ul>
        </div>
      </section>

      {/* Seniors and Teens */}
      <section className="bg-gray-100 py-16 px-6">
        <div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-10">
          <div className="bg-white rounded-3xl shadow-md p-8">
            <h2 className="text-3xl font-bold mb-4">Helping Seniors</h2>
            <p className="text-lg leading-relaxed">
              Taxes help fund programs that support senior citizens, including healthcare services,
              public transportation, retirement assistance, and community support programs.
              Paying taxes helps create safer and healthier communities for older adults.
            </p>
          </div>

          <div className="bg-white rounded-3xl shadow-md p-8">
            <h2 className="text-3xl font-bold mb-4">Helping Teenagers</h2>
            <p className="text-lg leading-relaxed">
              Taxes also help teenagers by funding schools, after-school programs, sports,
              libraries, scholarships, public parks, and youth community centers.
              These services help students learn, grow, and prepare for their future careers.
            </p>
          </div>
        </div>
      </section>

      {/* Where Money Goes */}
      <section className="max-w-6xl mx-auto py-16 px-6">
        <h2 className="text-4xl font-bold text-center mb-12">Where Does Tax Money Go?</h2>

        <div className="grid md:grid-cols-4 gap-6">
          {[
            {
              title: 'Education',
              text: 'Schools, teachers, technology, and student programs.'
            },
            {
              title: 'Healthcare',
              text: 'Hospitals, healthcare programs, and emergency services.'
            },
            {
              title: 'Transportation',
              text: 'Roads, buses, bridges, and public transportation systems.'
            },
            {
              title: 'Community Services',
              text: 'Public parks, firefighters, libraries, and safety programs.'
            }
          ].map((item, index) => (
            <div
              key={index}
              className="bg-white rounded-3xl shadow-lg p-6 hover:shadow-2xl transition"
            >
              <h3 className="text-2xl font-semibold mb-3">{item.title}</h3>
              <p className="text-lg">{item.text}</p>
            </div>
          ))}
        </div>
      </section>

      {/* Easy Tax Filing */}
      <section className="bg-blue-700 text-white py-16 px-6">
        <div className="max-w-5xl mx-auto text-center">
          <h2 className="text-4xl font-bold mb-6">Easy Tax Filing with X Tax</h2>
          <p className="text-xl leading-relaxed max-w-3xl mx-auto">
            X Tax makes paying taxes simple and stress-free. The website guides users step-by-step,
            explains forms clearly, and helps people feel confident while filing taxes online.
          </p>

          <div className="grid md:grid-cols-3 gap-6 mt-12">
            <div className="bg-white text-gray-800 rounded-3xl p-6 shadow-lg">
              <h3 className="text-2xl font-bold mb-2">1. Create an Account</h3>
              <p>Sign up in minutes with simple and secure information.</p>
            </div>

            <div className="bg-white text-gray-800 rounded-3xl p-6 shadow-lg">
              <h3 className="text-2xl font-bold mb-2">2. Follow the Guide</h3>
              <p>Answer easy questions and let X Tax organize your forms.</p>
            </div>

            <div className="bg-white text-gray-800 rounded-3xl p-6 shadow-lg">
              <h3 className="text-2xl font-bold mb-2">3. Submit Securely</h3>
              <p>Review your taxes and file online safely and quickly.</p>
            </div>
          </div>
        </div>
      </section>

      {/* Subscription Section */}
      <section className="max-w-5xl mx-auto py-20 px-6 text-center">
        <h2 className="text-4xl font-bold mb-4">Learn Taxes & Investing</h2>
        <p className="text-xl max-w-3xl mx-auto mb-10">
          Subscribe to learn how taxes work, how to file taxes correctly,
          and how to start investing money responsibly for your future.
        </p>

        <div className="bg-white shadow-2xl rounded-3xl p-10 border border-blue-100 max-w-xl mx-auto">
          <h3 className="text-3xl font-bold mb-4">Premium Learning Plan</h3>
          <p className="text-5xl font-extrabold text-blue-700 mb-4">$10<span className="text-xl font-medium">/month</span></p>
          <p className="text-lg mb-6">Start with a FREE 7-day trial and explore all lessons before subscribing.</p>

          <ul className="space-y-3 text-left text-lg mb-8">
            <li>✔ Step-by-step tax lessons</li>
            <li>✔ Beginner investing guides</li>
            <li>✔ Budgeting and saving tips</li>
            <li>✔ Interactive learning videos</li>
            <li>✔ AI tax learning assistant</li>
          </ul>

          <button className="bg-blue-700 text-white px-8 py-4 rounded-2xl text-lg font-semibold hover:scale-105 transition">
            Start Free Trial
          </button>
        </div>
      </section>

      {/* AI Talk Assistant */}
      <section className="bg-gray-100 py-20 px-6">
        <div className="max-w-4xl mx-auto">
          <h2 className="text-4xl font-bold text-center mb-10">AI Tax Helper</h2>

          <div className="bg-white rounded-3xl shadow-xl p-8 space-y-6">
            <div className="bg-blue-100 p-4 rounded-2xl w-fit max-w-md">
              <p>
                Hi! I’m the X Tax AI Assistant. I can help explain taxes,
                investments, savings, and how to file taxes online.
              </p>
            </div>

            <div className="bg-gray-200 p-4 rounded-2xl ml-auto w-fit max-w-md">
              <p>How do taxes help my community?</p>
            </div>

            <div className="bg-blue-100 p-4 rounded-2xl w-fit max-w-md">
              <p>
                Taxes help pay for schools, hospitals, transportation,
                public safety, parks, and programs that support seniors and teenagers.
              </p>
            </div>

            <div className="flex gap-3 mt-6">
              <input
                type="text"
                placeholder="Ask the AI Assistant a question..."
                className="flex-1 border rounded-2xl px-4 py-3 text-lg"
              />
              <button className="bg-blue-700 text-white px-6 py-3 rounded-2xl font-semibold">
                Send
              </button>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-10 px-6 text-center">
        <h3 className="text-2xl font-bold mb-3">X Tax</h3>
        <p className="max-w-2xl mx-auto text-lg">
          Making taxes easy to understand for everyone.
        </p>
        <p className="mt-6 text-sm text-gray-400">
          © 2026 X Tax. Educational purposes only.
        </p>
      </footer>
    </div>
  );
}
