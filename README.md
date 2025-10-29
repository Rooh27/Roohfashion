<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Rooh – Wear. Create. Inspire.</title>
<meta name="theme-color" content="#7c3aed">
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
<style>
  body { font-family: system-ui, -apple-system, Inter, sans-serif; background:#fafafa; color:#1e1e1e; margin:0; }
  header { position:sticky; top:0; background:rgba(255,255,255,.9); backdrop-filter:blur(8px); border-bottom:1px solid #eee; z-index:20; }
  .hero { background:linear-gradient(135deg,#7c3aed,#ec4899); color:white; }
  .card { transition:.3s; } .card:hover { transform:translateY(-4px); box-shadow:0 10px 24px rgba(0,0,0,.08); }
  .btn { display:inline-block; padding:.5rem 1rem; border-radius:.5rem; text-align:center; font-weight:500; }
  .btn-primary { background:#7c3aed; color:white; }
  .btn-light { background:white; color:#7c3aed; }
  .fab { position:fixed; bottom:1rem; right:1rem; background:#7c3aed; color:white; border-radius:9999px; width:3.5rem; height:3.5rem; font-size:1.5rem; display:flex; align-items:center; justify-content:center; box-shadow:0 6px 16px rgba(0,0,0,.3); }
</style>
</head>
<body>

<header>
  <div class="max-w-7xl mx-auto px-4 py-3 flex items-center gap-3">
    <div class="w-9 h-9 rounded-md bg-purple-600"></div>
    <strong class="text-xl">Rooh</strong>
    <nav class="ml-auto flex items-center gap-3">
      <a href="#products" class="hover:text-purple-600">Shop</a>
      <a href="#contact" class="hover:text-purple-600">Contact</a>
    </nav>
  </div>
</header>

<section class="hero text-center py-14">
  <h1 class="text-4xl font-extrabold">Wear. Create. Inspire.</h1>
  <p class="mt-2 opacity-90">Global lifestyle store – your style, your world.</p>
  <a href="#products" class="btn btn-light mt-5">Explore</a>