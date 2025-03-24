import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Github, Linkedin } from "lucide-react";
import { motion } from "framer-motion";

export default function TvasPortfolio() {
  return (
    <div className="bg-orange-50 min-h-screen text-gray-900 font-sans">
      <header className="bg-orange-300 shadow-md p-6 flex justify-between items-center">
        <h1 className="text-3xl font-bold text-orange-900">Tvas</h1>
        <nav className="space-x-4">
          <a href="#about" className="hover:underline">About</a>
          <a href="#projects" className="hover:underline">Projects</a>
          <a href="#skills" className="hover:underline">Skills</a>
          <a href="#contact" className="hover:underline">Contact</a>
        </nav>
      </header>

      <motion.section
        className="text-center py-20 bg-orange-100"
        initial={{ opacity: 0, y: -30 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 1 }}
      >
        <h2 className="text-5xl font-extrabold mb-4 text-orange-700">Hey, I'm Tvas</h2>
        <p className="text-xl mb-6">
          Urban Planner • Data Science Enthusiast • Web Developer
        </p>
        <a
          href="/resume.pdf"
          className="inline-block mt-4 bg-orange-500 text-white py-2 px-4 rounded-xl hover:bg-orange-600"
          download
        >
          Download Resume
        </a>
      </motion.section>

      <section id="about" className="p-10 bg-white">
        <h3 className="text-3xl font-bold text-orange-800 mb-4">About Me</h3>
        <p className="text-lg">
          I’m an Urban Planner with a passion for Data Science and Web Development.
          I love building tech-enabled planning tools and exploring the spatial
          dimension of data. I'm also a Naruto fan—so I channel that ninja energy
          into my work!
        </p>
      </section>

      <section id="projects" className="p-10 bg-orange-100">
        <h3 className="text-3xl font-bold text-orange-800 mb-4">Projects</h3>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
          <Card>
            <CardContent className="p-4">
              <h4 className="text-xl font-bold">Urban Data Dashboard</h4>
              <p className="text-sm">Visualizing planning data using D3 + Leaflet.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4">
              <h4 className="text-xl font-bold">Rental Housing Analysis</h4>
              <p className="text-sm">GCDA rental housing feasibility using Python.</p>
            </CardContent>
          </Card>
        </div>
      </section>

      <section id="skills" className="p-10 bg-white">
        <h3 className="text-3xl font-bold text-orange-800 mb-4">Skills</h3>
        <ul className="list-disc list-inside text-lg">
          <li>Urban Planning Tools (GIS, AutoCAD)</li>
          <li>Python (Pandas, Scikit-learn, Matplotlib)</li>
          <li>Web Dev (React, TailwindCSS)</li>
          <li>Data Visualization & Analysis</li>
        </ul>
      </section>

      <section id="contact" className="p-10 bg-orange-100">
        <h3 className="text-3xl font-bold text-orange-800 mb-4">Contact Me</h3>
        <p className="mb-4">Let’s connect and collaborate!</p>
        <div className="flex gap-4">
          <a href="https://github.com/tvasrajai" target="_blank" rel="noreferrer">
            <Github className="w-6 h-6 text-orange-700 hover:text-orange-900" />
          </a>
          <a href="https://linkedin.com/in/tvasrajai" target="_blank" rel="noreferrer">
            <Linkedin className="w-6 h-6 text-orange-700 hover:text-orange-900" />
          </a>
        </div>
      </section>

      <footer className="text-center p-4 bg-orange-300 text-orange-900">
        © {new Date().getFullYear()} Tvas Rajai. All rights reserved.
      </footer>
    </div>
  );
}
