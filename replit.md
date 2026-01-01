# Delta Diving & Marine Services Website

## Overview
Company website for Delta Diving & Marine Services, a marine services company based in Aqaba, Jordan since 2014. The site showcases their diving and marine services, safety credentials, and professional reputation.

## Recent Changes
- Built complete multi-page website with oceanic industrial design
- Implemented Deep Sea Blue (#0B3D5C) and Safety Orange (#FF6B35) color scheme
- Created Home, About Us, Services, Projects, and Contact pages
- Integrated company logo in navbar and footer
- Contact form now uses FormSubmit (formsubmit.co) - free service, no API keys needed
- Added company profile PDF for download

## User Preferences
- Large, prominent logo display
- Professional marine/industrial aesthetic
- Contact form must deliver to info@delta-diving.com
- SSL/HTTPS required for custom domain www.delta-diving.com

## Project Architecture
- Frontend: React with Vite, Tailwind CSS, shadcn/ui components
- Backend: Express server with PostgreSQL database
- Email: FormSubmit service (formsubmit.co) - sends form submissions to info@delta-diving.com
  - Note: First submission triggers confirmation email that must be clicked to activate
- Routing: wouter for client-side routing

## Key Files
- `client/src/pages/` - All website pages
- `client/src/components/layout/` - Navbar, Footer, Layout components
- `server/routes.ts` - API endpoints
- `attached_assets/image_1764615110853.png` - Company logo
