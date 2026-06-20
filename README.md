What it is
A single reusable navigation sidebar for the TradeHub platform. It's one self-contained React component (Sidebar.jsx) that gets dropped into a layout wrapper, so every page shows the same sidebar automatically — build once, use everywhere.
What's in it
The TradeHub logo at the top (clicks back to dashboard), followed by four grouped nav sections — Main Actions, Communication, Account & Settings, and Support & Legal — each with icons and labels that route to their respective pages. At the bottom sits the amber "Upgrade to Premium" card with a crown icon and gradient "View plans" button.
The smart bits
It takes three props that make it flexible: activeItem (highlights whichever page you're on), isPremium (hides the upgrade card once a user pays), and onNavigate (handles the routing). It's also responsive — on desktop it's a fixed sidebar, and on mobile it collapses into a hamburger menu that slides out as a drawer with a backdrop.
Where it stands
It's a working, production-quality component. Your developer connects it to TradeHub's real auth and routing — a small task — and it's ready to run across the platform.
Want this written up as a proper README for the GitHub repo? That'd give anyone landing on the repo this same explanation right on the page.
