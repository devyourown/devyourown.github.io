---
layout: default
title: "Home"
---

<div class="bg-gray-800 rounded-2xl shadow-xl p-8 max-w-4xl flex">
    <img
        src="assets/images/main.jpg"
        class="rounded-xl w-1/2"
        alt="Workspace"
    />
    <div class="ml-6 w-1/2">
        <h1 class="text-4xl font-bold">Hi! I'm Devyourown 👋</h1>
        <h2 class="text-xl text-gray-400 mt-2">
            A Software Engineer who loves Math, Algorithm.
        </h2>
        <p class="mt-4 text-gray-300">
            I'm also a fullstack developer. usually use Spring boot as a
            backend, Next.js as a frontend. This blog is my personal knowledge
            base on philosophy thoughts, programming, and the engineering.
        </p>
        <button
            class="mt-6 bg-pink-600 px-6 py-2 rounded-lg text-white font-semibold hover:bg-pink-500"
        >
            Let's Work Together
        </button>
    </div>
</div>
<div>{% include articles.html %}</div>
