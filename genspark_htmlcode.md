```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Power of Possibility for Young Minds</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #f8f9fa;
            color: #333;
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Montserrat', sans-serif;
        }
        .slide {
            min-height: 100vh;
            padding: 2rem;
            border-bottom: 1px solid #eaeaea;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        .accent-color {
            color: #3b82f6;
        }
        .secondary-color {
            color: #10b981;
        }
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        .gradient-bg {
            background: linear-gradient(135deg, #3b82f6 0%, #8b5cf6 100%);
        }
        .slide-content {
            max-width: 1200px;
            margin: 0 auto;
            width: 100%;
        }
        .year-tag {
            position: absolute;
            bottom: 1rem;
            right: 1rem;
            font-size: 0.8rem;
            opacity: 0.7;
        }
        .icon-box {
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 12px;
            color: white;
            font-size: 1.5rem;
        }
    </style>
</head>
<body>
    <!-- Title Slide -->
    <section class="slide bg-gradient-to-r from-blue-600 to-purple-600 text-white">
        <div class="slide-content flex flex-col items-center justify-center text-center">
            <h1 class="text-5xl md:text-6xl font-bold mb-6">Power of Possibility</h1>
            <h2 class="text-3xl md:text-4xl font-light mb-10">for Young Minds</h2>
            <p class="text-xl opacity-80 max-w-2xl">Empowering the next generation to dream big and achieve more</p>
            <div class="mt-16">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f680.svg" alt="Rocket" width="80" class="mx-auto">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Agenda Slide -->
    <section class="slide bg-white">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-12 text-blue-600">Agenda</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="space-y-6">
                    <div class="flex items-start">
                        <div class="icon-box bg-blue-500 mr-4">
                            <i class="fas fa-bullseye"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2">Mission & Vision</h3>
                            <p class="text-gray-600">Our purpose and what drives us forward</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="icon-box bg-green-500 mr-4">
                            <i class="fas fa-users"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2">Who We Are</h3>
                            <p class="text-gray-600">The team behind the initiative</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="icon-box bg-purple-500 mr-4">
                            <i class="fas fa-heart"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2">Why This Matters</h3>
                            <p class="text-gray-600">The impact on children's futures</p>
                        </div>
                    </div>
                </div>
                
                <div class="space-y-6">
                    <div class="flex items-start">
                        <div class="icon-box bg-yellow-500 mr-4">
                            <i class="fas fa-hand-holding-heart"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2">Our Request</h3>
                            <p class="text-gray-600">How you can help us make a difference</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="icon-box bg-red-500 mr-4">
                            <i class="fas fa-forward"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2">Next Steps</h3>
                            <p class="text-gray-600">The path forward for our initiative</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Our Big Dream Slide -->
    <section class="slide bg-blue-50">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-8 text-blue-600">Our Big Dream</h2>
            <div class="bg-white rounded-lg shadow-lg p-8 mb-10">
                <p class="text-lg leading-relaxed mb-6">
                    Hey there! We've got one simple goal - help kids believe in themselves and their dreams. Sounds cheesy? Maybe. But trust us, it's powerful stuff!
                </p>
                <p class="text-lg leading-relaxed">
                    We believe a little bit of positivity, self-belief, and some fun exercises in thinking big can change how kids see the world. Our dream is to bring this magic to your community and see small yet powerful changes.
                </p>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f31f.svg" alt="Sparkle" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Who We Are Slide -->
    <section class="slide bg-white">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-8 text-blue-600">Who We Are?</h2>
            <div class="bg-blue-50 rounded-lg shadow-md p-8 mb-10">
                <p class="text-lg leading-relaxed mb-6">
                    Just a bunch of dreamers! We're a passionate group. We live in Life Republic, Marunji, and just happen to be on the same wavelength - helping young, beautiful minds discover how awesome they truly are.
                </p>
                <p class="text-lg leading-relaxed">
                    We're not teachers or life coaches, but we do know a thing or two about turning tough situations into opportunities. And we believe in sharing that power with the next generation. Think of us as friendly mentors with big hearts.
                </p>
            </div>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mt-8">
                <div class="card bg-white p-4 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-blue-500 text-xl"></i>
                    </div>
                    <h4 class="font-medium">Vishal B</h4>
                </div>
                <div class="card bg-white p-4 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-purple-500 text-xl"></i>
                    </div>
                    <h4 class="font-medium">Nisha Shrivastava</h4>
                </div>
                <div class="card bg-white p-4 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-green-500 text-xl"></i>
                    </div>
                    <h4 class="font-medium">Purvi</h4>
                </div>
                <div class="card bg-white p-4 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-red-500 text-xl"></i>
                    </div>
                    <h4 class="font-medium">Dipali</h4>
                </div>
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Why This Matters Slide -->
    <section class="slide bg-blue-50">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-8 text-blue-600">Why This Matters?</h2>
            <h3 class="text-2xl font-semibold mb-6 text-blue-800">Little minds, big power</h3>
            
            <div class="grid md:grid-cols-2 gap-8 mb-12">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h4 class="text-xl font-semibold mb-4 text-blue-600">Here's the thing:</h4>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <span class="text-green-500 mr-2"><i class="fas fa-check-circle"></i></span>
                            <span>Life's tough for many kids. Some lose their confidence early, some just need a little nudge to dream bigger.</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-500 mr-2"><i class="fas fa-check-circle"></i></span>
                            <span>We want to teach them that they're capable of anything - all it takes is a little self-belief and the right mindset.</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-500 mr-2"><i class="fas fa-check-circle"></i></span>
                            <span>Our plan? Fun, interactive sessions thrice a month that are easy, practical, and leave them feeling like superheroes. 🦸‍♂️</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h4 class="text-xl font-semibold mb-4 text-blue-600">What we'll cover:</h4>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <span class="text-blue-500 mr-2"><i class="fas fa-star"></i></span>
                            <span>The power of self-belief.</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-blue-500 mr-2"><i class="fas fa-star"></i></span>
                            <span>Visualization (basically daydreaming with a purpose).</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-blue-500 mr-2"><i class="fas fa-star"></i></span>
                            <span>Goal setting in the coolest way possible.</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="text-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4aa.svg" alt="Strength" width="60" class="inline-block">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Science-Based Tools Slide -->
    <section class="slide bg-white">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-8 text-blue-600">Science-Based Tools</h2>
            <h3 class="text-2xl font-semibold mb-10 text-center text-gray-700">Latest tools in easiest form for building confidence & successful life</h3>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mb-12">
                <div class="card bg-blue-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-brain text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-blue-800">Reticular Activator System</h4>
                </div>
                
                <div class="card bg-purple-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-comment-dots text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-purple-800">NLP</h4>
                </div>
                
                <div class="card bg-green-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-wave-square text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-green-800">Science of Frequency & Energy</h4>
                </div>
                
                <div class="card bg-yellow-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-atom text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-yellow-800">Quantum Physics</h4>
                </div>
                
                <div class="card bg-red-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-dna text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-red-800">Epigenetics</h4>
                </div>
                
                <div class="card bg-indigo-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-book-open text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-indigo-800">Stories</h4>
                </div>
                
                <div class="card bg-pink-50 p-6 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-memory text-white text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-pink-800">Memory Techniques</h4>
                </div>
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- What Will Change Slide -->
    <section class="slide bg-blue-50">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-10 text-blue-600">What Will Change</h2>
            
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-hand-peace text-red-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Stop Bullying</h4>
                </div>
                
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-medal text-blue-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Build Confidence</h4>
                </div>
                
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-heart text-green-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Making Good Human Being</h4>
                </div>
                
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-microscope text-purple-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Increase Curiosity in Science</h4>
                </div>
                
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-yellow-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-sun text-yellow-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Give Hope</h4>
                </div>
                
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-bolt text-indigo-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Giving Them Their Power Back</h4>
                </div>
                
                <div class="card bg-white p-5 rounded-lg shadow-md text-center">
                    <div class="w-16 h-16 bg-pink-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-brain text-pink-500 text-xl"></i>
                    </div>
                    <h4 class="font-semibold text-gray-800">Increase Memory</h4>
                </div>
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Curriculum Slide 1 -->
    <section class="slide bg-white">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-6 text-blue-600">Curricular - Internal</h2>
            <div class="bg-gradient-to-r from-blue-500 to-blue-600 text-white rounded-t-lg p-4">
                <h3 class="text-xl font-semibold">Science of Frequency & Energy – 15-20 mins</h3>
            </div>
            <div class="bg-blue-50 rounded-b-lg p-6 shadow-md mb-10">
                <p class="mb-4">
                    This section will explain why it is important to behave right and what is a impact if they don't behave, 
                    how the energy played important role in life, we will cover below points.
                </p>
                <ul class="space-y-3 ml-5">
                    <li class="flex items-center">
                        <span class="text-blue-500 mr-2"><i class="fas fa-circle"></i></span>
                        <span>Electromagnetic being</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-blue-500 mr-2"><i class="fas fa-circle"></i></span>
                        <span>Why it's important (In most cases, why some people get's things done easily and other's not.)</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-blue-500 mr-2"><i class="fas fa-circle"></i></span>
                        <span>What are the reasons it get's depleted.</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-blue-500 mr-2"><i class="fas fa-circle"></i></span>
                        <span>How to improve it.</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-blue-500 mr-2"><i class="fas fa-circle"></i></span>
                        <span>We can ask them to prepare gratitude list (paying gratitude is one of the way to improve on energy).</span>
                    </li>
                </ul>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/26a1.svg" alt="Energy" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Curriculum Slide 2 -->
    <section class="slide bg-blue-50">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-6 text-blue-600">Curricular - Internal</h2>
            <div class="bg-gradient-to-r from-purple-500 to-purple-600 text-white rounded-t-lg p-4">
                <h3 class="text-xl font-semibold">Quantum Physics – 15-20 mins</h3>
            </div>
            <div class="bg-white rounded-b-lg p-6 shadow-md mb-10">
                <p class="mb-4">
                    In this section we will cover the basics of quantum physics and explain them how it can be used to build the confidence and better life.
                </p>
                <p class="mb-4">
                    Basically it involves the basic concept like it's the observer (you) who is creating the life, 
                    whatever you try to see / focus in life you get that.
                </p>
                <p class="mb-4">
                    We will explain the concept like internal voice where mind is listening to you every moment and 
                    how your internal voice play big role in what you can achieve and what not.
                </p>
                <p>
                    We will explain Reticular Activator System the filter of the mind which filters out the non important things 
                    and how it can be trained to make some thing important for you.
                </p>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/269b.svg" alt="Atom" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Curriculum Slide 3 -->
    <section class="slide bg-white">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-6 text-blue-600">Curricular - Internal</h2>
            <div class="bg-gradient-to-r from-green-500 to-green-600 text-white rounded-t-lg p-4">
                <h3 class="text-xl font-semibold">Epigenetic – 15-20 mins</h3>
            </div>
            <div class="bg-green-50 rounded-b-lg p-6 shadow-md mb-10">
                <p class="mb-4">
                    In this section we will cover the basics of epigenetic and how it is impacting their life and how it can change someone.
                </p>
                <p class="mb-4">
                    How they can use it in their life and make shift in their life.
                </p>
                <p>
                    We will share the stories how one become better when exposing the good environment and having good thoughts.
                </p>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f9ec.svg" alt="DNA" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Curriculum Slide 4 -->
    <section class="slide bg-blue-50">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-6 text-blue-600">Curricular - Internal</h2>
            <div class="bg-gradient-to-r from-yellow-500 to-yellow-600 text-white rounded-t-lg p-4">
                <h3 class="text-xl font-semibold">NLP & Memory Techniques – 20-30 mins</h3>
            </div>
            <div class="bg-white rounded-b-lg p-6 shadow-md mb-10">
                <p class="mb-4">
                    In this section we will explain basics of NLP (Neuro Linguistic Programming), conscious mind, 
                    subconscious mind, what is a role of subconscious mind and how NLP can be used for programming 
                    it for building confidence and any area of their life.
                </p>
                <p>
                    We will also share the memory techniques which can be used for remembering complex concepts.
                </p>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f9e0.svg" alt="Brain" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Curriculum Slide 5 -->
    <section class="slide bg-white">
        <div class="slide-content">
            <h2 class="text-4xl font-bold mb-6 text-blue-600">Curricular - Internal</h2>
            <div class="bg-gradient-to-r from-red-500 to-red-600 text-white rounded-t-lg p-4">
                <h3 class="text-xl font-semibold">Practice of some of the techniques, discussion, question answer – 30-40 mins</h3>
            </div>
            <div class="bg-red-50 rounded-b-lg p-6 shadow-md mb-10">
                <div class="grid md:grid-cols-3 gap-6">
                    <div class="bg-white p-4 rounded-lg shadow-sm text-center">
                        <div class="w-14 h-14 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-users text-red-500 text-xl"></i>
                        </div>
                        <h4 class="font-medium text-gray-800">Interactive Group Work</h4>
                    </div>
                    
                    <div class="bg-white p-4 rounded-lg shadow-sm text-center">
                        <div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-comments text-blue-500 text-xl"></i>
                        </div>
                        <h4 class="font-medium text-gray-800">Open Discussion</h4>
                    </div>
                    
                    <div class="bg-white p-4 rounded-lg shadow-sm text-center">
                        <div class="w-14 h-14 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-question-circle text-green-500 text-xl"></i>
                        </div>
                        <h4 class="font-medium text-gray-800">Q&A Session</h4>
                    </div>
                </div>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4ac.svg" alt="Discussion" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- What We're Asking Slide -->
    <section class="slide bg-gradient-to-r from-blue-600 to-purple-600 text-white">
        <div class="slide-content text-center">
            <h2 class="text-4xl font-bold mb-10">What We're Asking?</h2>
            <div class="bg-white bg-opacity-10 p-8 rounded-xl backdrop-filter backdrop-blur-sm shadow-lg max-w-3xl mx-auto">
                <h3 class="text-2xl font-semibold mb-6">Help Us Make It Happen</h3>
                <p class="text-lg mb-6">
                    We'd love your support to kick off this initiative in your community. We're asking for permission to organize 
                    small coaching sessions for kids aged 8 and above.
                </p>
                <p class="text-lg mb-8">
                    These sessions will be interactive, fun, and designed to leave a lasting positive impact.
                </p>
                <p class="text-xl font-medium">
                    Let's team up and inspire the next generation of dreamers and doers. Together, we can make something truly amazing happen!
                </p>
            </div>
            <div class="mt-10">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f91d.svg" alt="Handshake" width="80" class="mx-auto">
            </div>
        </div>
        <div class="year-tag text-white">20XX</div>
    </section>
    
    <!-- Q&A Slide -->
    <section class="slide bg-blue-50">
        <div class="slide-content text-center">
            <h2 class="text-4xl font-bold mb-8 text-blue-600">Q&A</h2>
            <div class="bg-white p-8 rounded-xl shadow-lg max-w-3xl mx-auto mb-10">
                <p class="text-xl text-gray-700 mb-4">We'd be happy to answer any questions you might have about our program.</p>
                <p class="text-lg text-gray-600">Schedule details to follow</p>
            </div>
            <div class="flex justify-center">
                <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/2753.svg" alt="Question" width="60">
            </div>
        </div>
        <div class="year-tag">20XX</div>
    </section>
    
    <!-- Thank You Slide -->
    <section class="slide bg-gradient-to-r from-blue-600 to-purple-600 text-white">
        <div class="slide-content text-center">
            <h2 class="text-5xl font-bold mb-12">Thank You</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 max-w-4xl mx-auto">
                <div class="bg-white bg-opacity-10 backdrop-filter backdrop-blur-md p-5 rounded-xl shadow-lg">
                    <div class="w-20 h-20 bg-white bg-opacity-20 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-white text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-medium">Vishal B</h4>
                </div>
                
                <div class="bg-white bg-opacity-10 backdrop-filter backdrop-blur-md p-5 rounded-xl shadow-lg">
                    <div class="w-20 h-20 bg-white bg-opacity-20 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-white text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-medium">Nisha Shrivastava</h4>
                </div>
                
                <div class="bg-white bg-opacity-10 backdrop-filter backdrop-blur-md p-5 rounded-xl shadow-lg">
                    <div class="w-20 h-20 bg-white bg-opacity-20 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-white text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-medium">Purvi</h4>
                </div>
                
                <div class="bg-white bg-opacity-10 backdrop-filter backdrop-blur-md p-5 rounded-xl shadow-lg">
                    <div class="w-20 h-20 bg-white bg-opacity-20 rounded-full flex items-center justify-center mx-auto mb-3">
                        <i class="fas fa-user text-white text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-medium">Dipali</h4>
                </div>
            </div>
            <div class="mt-12">
                <p class="text-xl">Let's inspire young minds together!</p>
            </div>
        </div>
        <div class="year-tag text-white">20XX</div>
    </section>

    <script>
        // Simple JavaScript for potential interaction
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.card');
            cards.forEach(card => {
                card.addEventListener('mouseenter', function() {
                    this.classList.add('shadow-lg');
                });
                card.addEventListener('mouseleave', function() {
                    this.classList.remove('shadow-lg');
                });
            });
        });
    </script>
</body>
</html>
```
