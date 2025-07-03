<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced CFOP Speedcubing Guide</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <!-- Chosen Palette: Warm Neutrals -->
    <!-- Application Structure Plan: The application is structured around two user-selected goals: "Sub-20" and "Sub-10". This choice forms the primary navigation, revealing a dedicated learning path for the user's current objective. Within each path, content is organized by CFOP stage (Cross, F2L, Last Layer) and Fundamentals, using an accordion interface. This nested, goal-oriented structure uses progressive disclosure to present a large amount of information in manageable chunks, preventing overwhelm and transforming the static report into a focused, interactive learning dashboard. Checklists allow users to track their mastery, providing a sense of accomplishment. A new splash screen is added as an initial gate, informing the user about external video resources before they access the main guide. -->
    <!-- Visualization & Content Choices: Report sections are converted to interactive components. Goals -> Buttons control main content visibility. Skills (Cross, F2L) -> Accordions organize techniques. Techniques (Keyhole, X-Cross) -> Styled cards present descriptions and drills. OLL Roadmap -> A CSS Grid visualizer interactively displays algorithm groups and details on click. Look-Ahead -> A flexbox diagram shows the "Spotting -> Tracking -> Knowing" progression. Progress -> A Chart.js donut chart dynamically visualizes the user's completion percentage based on checklist interactions. The splash screen uses simple text and a button. This design enhances engagement and clarifies complex information. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        .accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease-in-out;
        }
        .active .accordion-content {
            max-height: 5000px;
        }
        .active .accordion-icon {
            transform: rotate(180deg);
        }
        .oll-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(40px, 1fr));
            gap: 4px;
        }
        .oll-cell {
            width: 100%;
            padding-bottom: 100%;
            position: relative;
        }
        .oll-face {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-template-rows: repeat(3, 1fr);
            gap: 2px;
            padding: 2px;
        }
        .oll-sticker-y { background-color: #FFD700; }
        .oll-sticker-g { background-color: #A0A0A0; }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 250px;
            height: 250px;
            margin: auto;
        }
    </style>
</head>
<body class="bg-stone-100 text-stone-800">

    <div id="splash-page" class="fixed inset-0 bg-stone-200 flex items-center justify-center z-50 p-4">
        <div class="bg-white p-8 rounded-xl shadow-lg text-center max-w-md">
            <h2 class="text-3xl font-bold text-stone-900 mb-4">Important Resources</h2>
            <p class="text-lg text-stone-700 mb-6">All resources mentioned in this guide are for reference. Please search for the websites and videos (which are labeled) provided in the resource sections by yourself. THIS SITE IS SUPPOSED TO BE A PORTAL TO TRACK YOUR PROGRESS.</p>
            <button id="splash-ok-btn" class="bg-teal-600 text-white font-bold py-3 px-8 rounded-lg shadow-md hover:bg-teal-700 transition-colors">
                OK
            </button>
        </div>
    </div>

    <div id="main-content" class="container mx-auto p-4 md:p-8 max-w-7xl hidden">
        <header class="text-center mb-8">
            <h1 class="text-4xl md:text-5xl font-bold text-stone-900">Advanced CFOP Speedcubing Guide</h1>
            <p class="mt-2 text-lg text-stone-600">Your interactive roadmap from Sub-25 to Sub-10</p>
        </header>

        <main>
            <div id="goal-selection" class="flex flex-col md:flex-row justify-center gap-4 mb-8">
                <button data-goal="sub20" class="goal-btn bg-white border-2 border-teal-600 text-teal-700 font-bold py-4 px-8 rounded-lg shadow-lg hover:bg-teal-50 transition-transform transform hover:scale-105 w-full md:w-auto">
                    Phase 1: Path to Sub-20
                </button>
                <button data-goal="sub10" class="goal-btn bg-white border-2 border-stone-400 text-stone-600 font-bold py-4 px-8 rounded-lg shadow-lg hover:bg-stone-50 transition-transform transform hover:scale-105 w-full md:w-auto">
                    Phase 2: Road to Sub-10
                </button>
            </div>

            <div id="content-display">
                <!-- Content will be injected here -->
            </div>
        </main>
    </div>

    <script>
        const contentData = {
            sub20: {
                title: "Phase 1: The Path to Sub-20 Seconds",
                intro: "This initial phase focuses on solidifying foundational advanced techniques and optimizing your current CFOP stages. The goal is to eliminate common inefficiencies, build speed, and create a solid base for elite times.",
                progressId: 'sub20Progress',
                sections: [
                    {
                        title: 'Cross Optimization',
                        icon: '🎯',
                        content: [
                            { 
                                id: 's20_cross_1', 
                                title: 'Cross on Bottom & No Rotations', 
                                text: 'Crucial for advanced solvers. Construct the Cross on the bottom layer to eliminate cube rotations, save time, and maintain optimal hand positions for F2L.', 
                                drill: 'Practice solves with a strict "no cube rotations during Cross" rule.',
                                resource: 'BadMephisto Cross Tutorials (video)',
                                miniObjectives: [
                                    'Consistently solve cross on the bottom layer.',
                                    'Execute cross without any cube rotations.',
                                    'Maintain good hand positions for the next step.'
                                ]
                            },
                            { 
                                id: 's20_cross_2', 
                                title: 'Optimal Planning (8 moves or fewer)', 
                                text: 'Fully use the 15s inspection to plan the entire Cross. Insert pieces relative to each other first, then align the D-layer with one D\'/D/D2 move at the end.', 
                                drill: 'Daily 5-minute drills: Hand-scramble, plan Cross, execute, and analyze move count. Aim for 8 moves or less.',
                                resource: 'J Perm Cross Tips, CS Timer',
                                miniObjectives: [
                                    'Plan entire cross within 15 seconds inspection.',
                                    'Achieve cross solutions in 8 moves or less consistently.',
                                    'Learn to insert pieces relative to each other before final alignment.'
                                ]
                            },
                        ]
                    },
                    {
                        title: 'F2L Efficiency',
                        icon: '🧩',
                        content: [
                             { 
                                id: 's20_f2l_1', 
                                title: 'Rotationless F2L & Back Slotting', 
                                text: 'The primary goal is to insert all F2L pairs without cube rotations (y/y\'). Prioritize solving pairs into the back slots first to improve visibility for the remaining pairs.', 
                                drill: 'Practice slow solves focusing on recognizing and executing back-slot insertions without rotating.',
                                resource: 'BadMephisto F2L (video), Reddit Cubers (F2L Tips)',
                                miniObjectives: [
                                    'Insert all F2L pairs without cube rotations.',
                                    'Consistently prioritize and solve back slots first.',
                                    'Improve recognition of back slot cases.'
                                ]
                            },
                            { 
                                id: 's20_f2l_2', 
                                title: 'Left-Hand F2L', 
                                text: 'Improve left-hand dexterity to efficiently execute mirrored F2L cases. This is key to reducing rotations and improving flow.', 
                                drill: 'Isolate and drill your mirrored F2L cases using your left hand.',
                                resource: 'Reddit Cubers (F2L Tips)',
                                miniObjectives: [
                                    'Improve left-hand turning speed and accuracy.',
                                    'Efficiently execute mirrored F2L cases with left hand.',
                                    'Reduce pauses when using left-hand solutions.'
                                ]
                            },
                            { 
                                id: 's20_f2l_3', 
                                title: 'Algorithmic F2L (Tricky Cases)', 
                                text: 'While F2L is largely intuitive, supplement your skills by learning algorithms for specific tricky cases where they offer a clear speed advantage.', 
                                drill: 'Use AlgDB.net to identify and drill complex F2L cases (e.g., cases 35-41).',
                                resource: 'AlgDB.net, J Perm F2L Algs',
                                miniObjectives: [
                                    'Identify 5-10 tricky F2L cases that benefit from algorithms.',
                                    'Memorize and execute algorithms for these cases smoothly.',
                                    'Integrate algorithmic F2L into regular solves.'
                                ]
                            },
                            { 
                                id: 's20_f2l_4', 
                                title: 'Intro to Keyhole & Pseudoslotting', 
                                text: 'Begin to understand Keyhole (using an empty slot to solve pieces) and Pseudoslotting (solving two pairs with one sequence). The goal here is recognition, not mastery.', 
                                drill: 'During untimed solves, look for opportunities where an edge is solved and its corner is easy to insert via the "keyhole".',
                                resource: 'CubeSkills Multi-slotting, Speedsolving Wiki',
                                miniObjectives: [
                                    'Understand the concept of Keyhole F2L.',
                                    'Recognize basic Keyhole opportunities in solves.',
                                    'Familiarize yourself with the concept of Pseudoslotting.'
                                ]
                            },
                        ]
                    },
                    {
                        title: 'Last Layer Polish',
                        icon: '✨',
                        content: [
                            { 
                                id: 's20_ll_1', 
                                title: 'Full PLL Execution Speed', 
                                text: 'You know full PLL, now perfect it. Drill individual cases until they are pure muscle memory. Focus on recognizing cases from just two sides to minimize pauses.', 
                                drill: 'Use an algorithm trainer to identify and hammer your slowest PLL cases.',
                                resource: 'J Perm PLL Trainer, SpeedCubeDB (PLL), Bestsiteever.net (PLL)',
                                miniObjectives: [
                                    'Drill all PLL algorithms to muscle memory.',
                                    'Improve PLL recognition from two sides of the cube.',
                                    'Reduce pauses before and during PLL execution.'
                                ]
                            },
                            { 
                                id: 's20_ll_2', 
                                title: 'Refine 2-Look OLL', 
                                text: 'Accelerate your 2-Look OLL by anticipating the corner orientation while solving the edge orientation. This reduces the "second look" pause to almost nothing.', 
                                drill: 'Practice OLL edge orientation, but instead of stopping to look, try to predict the subsequent corner case.',
                                resource: 'J Perm OLL Trainer, CubeSkills (2-Look OLL), Bestsiteever.net (OLL)',
                                miniObjectives: [
                                    'Anticipate corner orientation during 2-Look OLL edge orientation.',
                                    'Minimize pause between OLL edge and corner steps.',
                                    'Execute 2-Look OLL with fewer than 2 seconds recognition time.'
                                ]
                            },
                             { 
                                id: 's20_ll_3', 
                                title: 'Begin Transition to Full OLL', 
                                text: 'Full OLL is essential for the next level. Start learning the 57 algs systematically. Don\'t try to learn them all at once.', 
                                drill: 'Start by learning the easiest OLL groups: Sune/Anti-Sune, and other simple shapes. Add 1-2 new algs per day.',
                                resource: 'J Perm Easiest OLLs (video), Cube.Academy (OLL), SpeedCubeDB (OLL)',
                                miniObjectives: [
                                    'Learn the Sune and Anti-Sune OLL algorithms.',
                                    'Learn 5-10 of the easiest Full OLL cases.',
                                    'Practice recognizing these new OLL cases.'
                                ]
                            },
                        ]
                    },
                    {
                        title: 'Fundamental Speed Enhancers',
                        icon: '🚀',
                        content: [
                           { 
                                id: 's20_fun_1', 
                                title: 'Look-Ahead: The "Tracking" Stage', 
                                text: 'This is the most critical skill. While solving your current F2L pair, your eyes should be actively finding and *tracking* the pieces for your *next* pair. This eliminates the pause between pairs.', 
                                drill: 'Perform slow solves (e.g., at 1 turn per second). The slow pace forces your brain to look ahead. This is the #1 drill for improvement.',
                                resource: 'CubeSkills Look-Ahead, J Perm Look-Ahead (video)',
                                miniObjectives: [
                                    'Practice slow solves to force look-ahead.',
                                    'Actively track pieces for the next F2L pair while solving the current one.',
                                    'Reduce pauses between F2L pairs to under 0.5 seconds.'
                                ]
                            },
                             { 
                                id: 's20_fun_2', 
                                title: 'Turning Speed & Accuracy', 
                                text: 'Focus on smooth, accurate turning over uncontrolled speed. Lock-ups and mis-turns kill look-ahead and flow. A slightly tighter cube can help build accuracy.', 
                                drill: 'Practice turning with a metronome to develop a consistent, rhythmic turning style.',
                                resource: 'Chris Olson Finger Tricks (video)',
                                miniObjectives: [
                                    'Achieve consistent turning speed without lock-ups.',
                                    'Improve accuracy of turns, minimizing mis-turns.',
                                    'Practice finger tricks for all basic moves (R, U, F, etc.).'
                                ]
                            },
                        ]
                    }
                ]
            },
            sub10: {
                title: "Phase 2: The Road to Sub-10 Seconds",
                intro: "Achieving sub-10 requires refining all previous stages to an elite level. This phase is about maximizing efficiency, seamless transitions, and advanced predictive abilities.",
                progressId: 'sub10Progress',
                sections: [
                    {
                        title: 'Cross & X-Cross Mastery',
                        icon: '🎯',
                        content: [
                            { 
                                id: 's10_cross_1', 
                                title: 'Consistent X-Cross Execution', 
                                text: 'Consistently identify and execute X-Crosses (Cross + first F2L pair simultaneously). This should become a standard part of your solves, moving beyond simple cases.', 
                                drill: 'During inspection, always search for an X-Cross solution. Practice scrambles specifically designed to have X-Cross opportunities.',
                                resource: 'J Perm X-Cross Tutorial (video)',
                                miniObjectives: [
                                    'Consistently identify X-Cross opportunities in inspection.',
                                    'Execute X-Crosses smoothly in at least 50% of solves.',
                                    'Reduce X-Cross execution time to under 2 seconds.'
                                ]
                            },
                            { 
                                id: 's10_cross_2', 
                                title: 'Advanced Planning: Cross + 2', 
                                text: 'Extend your inspection to plan the Cross and the first F2L pair, and ideally, track the pieces for the second pair. This ensures a seamless transition and incredible flow.', 
                                drill: 'Dedicate solves to only planning Cross+1. Once consistent, try to track the second pair.',
                                resource: 'J Perm Advanced Cross Planning (video)',
                                miniObjectives: [
                                    'Plan Cross and first F2L pair during inspection.',
                                    'Track pieces for the second F2L pair during Cross execution.',
                                    'Achieve seamless transition from Cross to first F2L pair.'
                                ]
                            },
                        ]
                    },
                    {
                        title: 'F2L Advanced Techniques',
                        icon: '🧩',
                        content: [
                            { 
                                id: 's10_f2l_1', 
                                title: 'Advanced Multi-Slotting', 
                                text: 'Master inserting F2L pairs into any slot without rotation, using advanced and sometimes non-intuitive insertions that can influence other pieces favorably.', 
                                drill: 'Watch top solver examples and analyze how they solve pairs into the back-left slot, for instance. Recreate their solutions.',
                                resource: 'CubeSkills Multi-slotting',
                                miniObjectives: [
                                    'Master rotationless insertion into all four slots.',
                                    'Learn and apply advanced multi-slotting techniques.',
                                    'Analyze top solver videos to replicate efficient F2L solutions.'
                                ]
                            },
                            { 
                                id: 's10_f2l_2', 
                                title: 'Intentional Pseudoslotting', 
                                text: 'Move from accidental to intentional pseudoslotting. Actively look for opportunities where a solved corner and an edge can be combined to solve two pairs in one fluid motion.', 
                                drill: 'Analyze solves to find missed pseudoslotting opportunities. This requires a deep visual understanding of piece interaction.',
                                resource: 'Speedsolving Wiki Pseudoslotting',
                                miniObjectives: [
                                    'Actively search for pseudoslotting opportunities in solves.',
                                    'Execute pseudoslotting intentionally to solve two pairs at once.',
                                    'Develop a deep visual understanding of piece interaction for pseudoslotting.'
                                ]
                            },
                        ]
                    },
                    {
                        title: 'Full OLL & PLL Mastery',
                        icon: '✨',
                        content: [
                            { 
                                id: 's10_ll_1', 
                                title: 'Full OLL Recognition & Execution', 
                                text: 'Master all 57 OLL algorithms for a true one-look last layer. Focus on instant recognition from any angle.', 
                                drill: 'Use algorithm trainers daily. Focus on your 5 slowest OLLs until they become your fastest.',
                                resource: 'J Perm OLL Trainer, SpeedCubeDB (OLL), Bestsiteever.net (OLL)',
                                miniObjectives: [
                                    'Memorize all 57 Full OLL algorithms.',
                                    'Achieve instant recognition of all OLL cases from any angle.',
                                    'Execute OLL algorithms with minimal pauses.'
                                ]
                            },
                            { 
                                id: 's10_ll_2', 
                                title: 'Advanced PLL Recognition', 
                                text: 'Optimize PLL by exploring alternative, more finger-trick friendly algorithms. Practice recognizing the PLL case during the OLL execution, or even from the last F2L pair.', 
                                drill: 'For common OLLs (like Sune), try to predict the subsequent PLL case before the OLL is finished.',
                                resource: 'J Perm Advanced PLL Recognition (video), SpeedCubeDB (PLL)',
                                miniObjectives: [
                                    'Predict PLL case during OLL execution.',
                                    'Explore and adopt faster, finger-trick friendly PLL algorithms.',
                                    'Achieve seamless transition from OLL to PLL.'
                                ]
                            },
                        ]
                    },
                     {
                        title: 'Elite Fundamentals',
                        icon: '🚀',
                        content: [
                           { 
                                id: 's10_fun_1', 
                                title: 'Look-Ahead: The "Knowing" Stage', 
                                text: 'The final evolution of look-ahead. You don\'t just track pieces; you *know* where they will end up after your current move sequence. This allows for proactive planning and zero hesitation.', 
                                drill: 'This develops naturally from thousands of slow, deliberate solves. It\'s about building a deep, intuitive model of the cube in your mind.',
                                resource: 'CubeSkills Look-Ahead',
                                miniObjectives: [
                                    'Develop an intuitive model of piece trajectories on the cube.',
                                    'Proactively plan moves based on predicted piece positions.',
                                    'Achieve near-zero hesitation between all stages of the solve.'
                                ]
                            },
                             { 
                                id: 's10_fun_2', 
                                text: 'Eliminate the micro-pauses between every single stage: Cross -> F2L -> OLL -> PLL. This is achieved by your look-ahead skills predicting the next step before the current one is complete.', 
                                drill: 'Use a multi-phase timer to identify where you are pausing. Is it after the last F2L pair? Or after OLL? Target that specific transition.',
                                resource: 'csTimer, Cubeast',
                                miniObjectives: [
                                    'Identify and eliminate micro-pauses between Cross and F2L.',
                                    'Identify and eliminate micro-pauses between F2L and OLL.',
                                    'Identify and eliminate micro-pauses between OLL and PLL.'
                                ]
                            },
                        ]
                    }
                ]
            }
        };

        const splashPage = document.getElementById('splash-page');
        const mainContent = document.getElementById('main-content');
        const splashOkBtn = document.getElementById('splash-ok-btn');

        const goalBtns = document.querySelectorAll('.goal-btn');
        const contentDisplay = document.getElementById('content-display');
        let activeGoal = 'sub20';
        let progressChart = null;

        let appState = {
            sub20: {},
            sub10: {}
        };
        
        function loadState() {
            const savedState = localStorage.getItem('speedcubingProgress');
            if (savedState) {
                appState = JSON.parse(savedState);
            } else {
                // Initialize state if nothing is saved
                Object.keys(contentData).forEach(goalKey => {
                    contentData[goalKey].sections.forEach(section => {
                        section.content.forEach(item => {
                            // Initialize mini-objectives state
                            appState[goalKey][item.id] = item.miniObjectives ? item.miniObjectives.map(() => false) : false;
                        });
                    });
                });
            }
        }
        
        function saveState() {
            localStorage.setItem('speedcubingProgress', JSON.stringify(appState));
        }

        function renderContent(goal) {
            activeGoal = goal;
            const data = contentData[goal];
            let totalTasks = 0;
            let completedTasks = 0;

            const sectionsHtml = data.sections.map(section => {
                const itemsHtml = section.content.map(item => {
                    const isItemChecked = appState[goal][item.id] && (typeof appState[goal][item.id] === 'boolean' ? appState[goal][item.id] : appState[goal][item.id].every(b => b));
                    
                    let miniObjectivesHtml = '';
                    if (item.miniObjectives && item.miniObjectives.length > 0) {
                        miniObjectivesHtml = `
                            <div class="mt-4 pt-4 border-t border-stone-200">
                                <h5 class="text-md font-semibold text-stone-700 mb-2">Mini Objectives:</h5>
                                <ul class="list-disc list-inside text-sm text-stone-600 space-y-1">
                                    ${item.miniObjectives.map((obj, index) => {
                                        const isMiniObjectiveChecked = appState[goal][item.id] && appState[goal][item.id][index];
                                        return `
                                            <li class="flex items-center">
                                                <input type="checkbox" data-parent-id="${item.id}" data-index="${index}" class="mini-objective-checkbox h-4 w-4 rounded text-teal-600 focus:ring-teal-500 border-gray-300 mr-2 cursor-pointer" ${isMiniObjectiveChecked ? 'checked' : ''}>
                                                <span>${obj}</span>
                                            </li>
                                        `;
                                    }).join('')}
                                </ul>
                            </div>
                        `;
                    }

                    // Calculate progress for the main task checkbox based on mini-objectives
                    if (item.miniObjectives && item.miniObjectives.length > 0) {
                        const completedMiniObjectives = appState[goal][item.id].filter(b => b).length;
                        if (completedMiniObjectives === item.miniObjectives.length) {
                            totalTasks++;
                            completedTasks++;
                        } else {
                            totalTasks++; // Still count as a task, but not completed
                        }
                    } else {
                        // For items without mini-objectives, use the direct boolean state
                        totalTasks++;
                        if (appState[goal][item.id]) {
                            completedTasks++;
                        }
                    }

                    return `
                        <div class="bg-stone-50 p-4 rounded-lg mb-3 border border-stone-200">
                            <div class="flex items-start justify-between">
                                <h4 class="text-lg font-semibold text-stone-800">${item.title}</h4>
                                <!-- Main checkbox now reflects completion of all mini-objectives or its own state -->
                                <input type="checkbox" data-id="${item.id}" class="task-checkbox h-5 w-5 rounded text-teal-600 focus:ring-teal-500 border-gray-300 cursor-pointer" ${isItemChecked ? 'checked' : ''} ${item.miniObjectives && item.miniObjectives.length > 0 ? 'disabled' : ''}>
                            </div>
                            <p class="mt-2 text-stone-600">${item.text}</p>
                            <p class="mt-3 text-sm font-medium text-teal-700 bg-teal-50 p-2 rounded-md"><span class="font-bold">Drill:</span> ${item.drill}</p>
                            ${item.resource ? `<p class="mt-3 text-sm text-stone-500"><strong>Resources:</strong> ${item.resource}</p>` : ''}
                            ${miniObjectivesHtml}
                        </div>
                    `;
                }).join('');

                return `
                    <div class="accordion-item bg-white rounded-lg shadow-md mb-4">
                        <div class="accordion-header flex justify-between items-center p-4 cursor-pointer">
                            <h3 class="text-xl font-bold flex items-center gap-3"><span>${section.icon}</span> ${section.title}</h3>
                            <span class="accordion-icon text-2xl text-stone-400 transition-transform">▼</span>
                        </div>
                        <div class="accordion-content px-4 pb-2">
                            ${itemsHtml}
                        </div>
                    </div>
                `;
            }).join('');
            
            contentDisplay.innerHTML = `
                <div class="bg-white p-6 rounded-xl shadow-lg">
                    <div class="flex flex-col md:flex-row gap-8">
                        <div class="flex-grow">
                            <h2 class="text-3xl font-bold mb-1">${data.title}</h2>
                            <p class="text-stone-600 mb-6">${data.intro}</p>
                            ${sectionsHtml}
                        </div>
                        <div class="w-full md:w-1/3 flex-shrink-0">
                            <div class="bg-stone-50 p-4 rounded-lg sticky top-8">
                                <h3 class="text-xl font-bold text-center mb-4">Your Progress</h3>
                                <div class="chart-container">
                                    <canvas id="${data.progressId}"></canvas>
                                </div>
                                <p id="${data.progressId}-text" class="text-center font-bold text-2xl mt-4"></p>
                            </div>
                        </div>
                    </div>
                </div>
            `;
            updateChart(data.progressId, completedTasks, totalTasks);
            addEventListeners();
        }

        function updateChart(canvasId, completed, total) {
            const ctx = document.getElementById(canvasId).getContext('2d');
            const percentage = total > 0 ? Math.round((completed / total) * 100) : 0;
            const progressText = document.getElementById(`${canvasId}-text`);
            if(progressText) {
                progressText.textContent = `${percentage}% Complete`;
            }

            const chartData = {
                labels: ['Completed', 'Remaining'],
                datasets: [{
                    data: [completed, total - completed],
                    backgroundColor: ['#0d9488', '#e7e5e4'],
                    borderColor: ['#0d9488', '#e7e5e4'],
                    hoverBackgroundColor: ['#0f766e', '#d6d3d1'],
                    borderWidth: 1,
                    cutout: '70%',
                }]
            };

            if (progressChart) {
                progressChart.destroy();
            }

            progressChart = new Chart(ctx, {
                type: 'doughnut',
                data: chartData,
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { display: false },
                        tooltip: { enabled: false }
                    }
                }
            });
        }
        
        function handleCheckboxChange(e) {
            const checkbox = e.target;
            const id = checkbox.dataset.id;
            
            // If it's a main task checkbox (no parent-id), update its boolean state
            if (!checkbox.dataset.parentId) {
                appState[activeGoal][id] = checkbox.checked;
            }
            saveState();
            
            // Recalculate and update chart
            const data = contentData[activeGoal];
            let totalTasks = 0;
            let completedTasks = 0;
            data.sections.forEach(section => {
                section.content.forEach(item => {
                    if (item.miniObjectives && item.miniObjectives.length > 0) {
                        const completedMiniObjectives = appState[activeGoal][item.id].filter(b => b).length;
                        if (completedMiniObjectives === item.miniObjectives.length) {
                            totalTasks++;
                            completedTasks++;
                        } else {
                            totalTasks++;
                        }
                    } else {
                        totalTasks++;
                        if (appState[activeGoal][item.id]) {
                            completedTasks++;
                        }
                    }
                });
            });
            updateChart(data.progressId, completedTasks, totalTasks);
        }

        function handleMiniObjectiveChange(e) {
            const checkbox = e.target;
            const parentId = checkbox.dataset.parentId;
            const index = parseInt(checkbox.dataset.index);

            if (Array.isArray(appState[activeGoal][parentId])) {
                appState[activeGoal][parentId][index] = checkbox.checked;
            } else {
                // If somehow not an array, initialize it
                const item = contentData[activeGoal].sections.flatMap(s => s.content).find(i => i.id === parentId);
                if (item && item.miniObjectives) {
                    appState[activeGoal][parentId] = item.miniObjectives.map((_, i) => i === index ? checkbox.checked : false);
                }
            }
            saveState();

            // Update the parent task checkbox based on mini-objectives
            const parentTaskCheckbox = document.querySelector(`.task-checkbox[data-id="${parentId}"]`);
            if (parentTaskCheckbox) {
                const allMiniObjectivesCompleted = appState[activeGoal][parentId].every(b => b);
                parentTaskCheckbox.checked = allMiniObjectivesCompleted;
            }
            
            // Recalculate and update chart
            const data = contentData[activeGoal];
            let totalTasks = 0;
            let completedTasks = 0;
            data.sections.forEach(section => {
                section.content.forEach(item => {
                    if (item.miniObjectives && item.miniObjectives.length > 0) {
                        const completedMiniObjectives = appState[activeGoal][item.id].filter(b => b).length;
                        if (completedMiniObjectives === item.miniObjectives.length) {
                            totalTasks++;
                            completedTasks++;
                        } else {
                            totalTasks++;
                        }
                    } else {
                        totalTasks++;
                        if (appState[activeGoal][item.id]) {
                            completedTasks++;
                        }
                    }
                });
            });
            updateChart(data.progressId, completedTasks, totalTasks);
        }


        function addEventListeners() {
            document.querySelectorAll('.accordion-header').forEach(header => {
                header.addEventListener('click', () => {
                    header.parentElement.classList.toggle('active');
                });
            });
            document.querySelectorAll('.task-checkbox').forEach(checkbox => {
                checkbox.addEventListener('change', handleCheckboxChange);
            });
            document.querySelectorAll('.mini-objective-checkbox').forEach(checkbox => {
                checkbox.addEventListener('change', handleMiniObjectiveChange);
            });
        }
        
        goalBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const goal = btn.dataset.goal;
                renderContent(goal);

                goalBtns.forEach(b => {
                    b.classList.remove('bg-teal-600', 'text-white', 'border-teal-600');
                    b.classList.add('bg-white', 'text-stone-600', 'border-stone-400');
                });

                btn.classList.add('bg-teal-600', 'text-white', 'border-teal-600');
                btn.classList.remove('bg-white', 'text-stone-600', 'border-stone-400');
            });
        });

        splashOkBtn.addEventListener('click', () => {
            splashPage.classList.add('hidden');
            mainContent.classList.remove('hidden');
            // Trigger initial content load after splash screen
            document.querySelector('[data-goal="sub20"]').click();
        });

        // Initial load of state, but don't render content until splash is dismissed
        loadState();

    </script>
</body>
</html>
