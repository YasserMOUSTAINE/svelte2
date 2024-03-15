<script>
    import "../app.css"
</script>
<body>
    
    <div class="h-5 bg-blueGray-50 text-white">
        <nav class=" p-1 bg-blue-900 drop-shadow-lg flex gap-2 text-white ">
            <div class="mt-2">
                <span class="flex pl-40 ml-10 mr-4">
                    <div >
                        <svg  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M9.315 7.584C12.195 3.883 16.695 1.5 21.75 1.5a.75.75 0 0 1 .75.75c0 5.056-2.383 9.555-6.084 12.436A6.75 6.75 0 0 1 9.75 22.5a.75.75 0 0 1-.75-.75v-4.131A15.838 15.838 0 0 1 6.382 15H2.25a.75.75 0 0 1-.75-.75 6.75 6.75 0 0 1 7.815-6.666ZM15 6.75a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" clip-rule="evenodd" />
                            <path d="M5.26 17.242a.75.75 0 1 0-.897-1.203 5.243 5.243 0 0 0-2.05 5.022.75.75 0 0 0 .625.627 5.243 5.243 0 0 0 5.022-2.051.75.75 0 1 0-1.202-.897 3.744 3.744 0 0 1-3.008 1.51c0-1.23.592-2.323 1.51-3.008Z" />
                        </svg>
                    </div>
                    <div>
                      <ul>
                        <li class="nav-style">Dashboard</li>
                        <li class="nav-style">Projects</li>
                        <li class="nav-style">Template</li>
                        <li class="nav-style">Settings</li>
                    </ul>	
                    </div>					  
                </span>
                </div>
                <div class="flex justify-end ml-60">
                    <div>
                        <ul class="pt-3 pr-2">
                            <button class="w-10 h-5 rounded-full bg-white flex items-center transition duration-300 focus:outline-none shadow">
                                <div id="switch-toggle" class="w-6 h-6 relative rounded-full transition duration-500 transform bg-yellow-500 -translate-x-2 p-1 text-white ">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z" />
                                    </svg>
                                </div>
                            </button>
                        </ul>
                    </div>
                    <div class="" >
                        <a href="/" class="justify-self-cente ml-2">Webwize Studio B.V.</a>
                        <div>
                            
                            <a href="/">Yasser Moustaine</a>
                            <a href="/">Logout</a>
                        </div>
                    </div>
                </div>   
            </nav>

        <div class="text-black text-sm bg-slate-200 p-3 pl-20">
            <p class=" text-gray-500"><a href="/" class=" text-blue-400 font-bold">Did you know?</a> Want to learn more about Git? We've written a bunch of <a href="/" class=" text-blue-400 font-bold">free Git tutorials</a> on our website</p>
        </div>
        <div class=" text-black shadow-[rgba(0,_0,_0,_0.4)_0px_30px_90px] h-80 bg-[#FFFFFF] grid grid-cols-12 grid-rows-2 border-b-2 ">
            <div class=" col-span-8">
                <div class=" text-xl py-3 font-bold ml-20 border-b-2 border-spacing-1 border-gray-300">
                    <p>Account Activity</p>
                </div>
                <br>
                <div class=" ml-20 rounded-md bg-gray-100 py-5 border-2 text-center">
                    <p class=" text-base font-semibold text-gray-600">No recent activity!</p>
                    <p class=" text-sm text-gray-600">Looks like you haven't done anything in DeployHQ lately.</p>
                </div>
            </div>
            <div class=" py-7 pl-10">
                <table class="border w-72">
                    <tbody>
                    <tr class="border text-base font-semibold">
                        <td>Your projects</td>
                        
                    </tr>
                    <tr class="border border-spacing-3">
                        <td>alpha-api.webwize.studio</td>
                    </tr>
                    <tr class="border">
                        <td>cms.webwize.studio</td>
                    </tr>
                    <tr class="border">
                        <td>console.webwize.studio</td>
                    </tr>
                    <tr class="border">
                        <td>editor-api.webwize.studio</td>
                    </tr>
                    <tr class="border">
                        <td>editor.webwize.studio</td>
                    </tr>
                    <tr class="border">
                        <td>myaccount.webwize.studio</td>
                    </tr>
                    <tr class="border">
                        <td>sso.webwize.studio</td>
                    </tr>
                </tbody>
                </table>
            </div>
        </div>
        <div class=" bg-[#FFFFFF] h-11 border-b-2 border-gray-400">
            <p class=" font-semibold text-center text-black pt-2">How happy are you with DeployHQ? <a href="/" class="text-blue-600">Let us know</a></p>
        </div>
        <footer>
            <div class=" bg-[#FFFFFF] grid grid-cols-7 gap-4 ">
                <div class=" col-span-1"></div>
                <div class=" col-span-1 py-8 ">
                    <p class=" text-xl font-bold text-gray-500">Krystal</p>
                    <p class=" text-xs text-gray-500">2024-ALL rights reserved</p>
                </div>
                <div class=" col-span-1 py-10 pl-5">
                    <ul>
                        <li class=" li-title">About</li>
                        <li class="li-footer"><a href="/">About DeployHQ</a></li>
                        <li class="li-footer"><a href="/">Blog</a></li>
                        <li class="li-footer"><a href="/">Security</a></li>
                        <li class="li-footer"><a href="/">Privacy Policy</a></li>
                        <li class="li-footer"><a href="/">Terms of Service</a></li>
                        <li class="li-footer"><a href="/">Edit Cookies</a></li>
                    </ul>
                </div>
                <div class=" col-span-1 py-10 pl-5">
                    <ul>
                        <li class="li-title"><a href="/">Resources</a></li>
                        <li class="li-footer"><a href="/">Help & Support</a></li>
                        <li class="li-footer"><a href="/">Service Status</a></li>
                    </ul>
                </div>
                <div class=" col-span-1 py-10 pl-5">
                    <ul>
                        <li class="li-title"><a href="/">Other Products</a></li>
                        <li class="li-footer"><a href="/">Cloud Platform</a></li>
                        <li class="li-footer"><a href="/">Shared Hosting</a></li>
                        <li class="li-footer"><a href="/">WordPress Hosting</a></li>
                        <li class="li-footer"><a href="/">Entreprise Hosting</a></li>
                        <li class="li-footer"><a href="/">Codebase</a></li>
                        <li class="li-footer"><a href="/">Sirpotly</a></li>
                    </ul>
                </div>
                <div class=" col-span-1"></div>
                <div class=" col-span-1"></div>
            </div>
        </footer>
    </div>
    
    
    
    
</body>