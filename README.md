ProGlow → AI-powered booking & client glow-up system for elite estheticians, lash techs, PMU artists & med-spas. Zero no-shows, auto-rebooks, AI skin/lash analysis, private portals, Stripe deposits. Next.js 15 · TypeScript · Supabase · Tailwind. Star now for beta access + lifetime deals.
# 1. Clone the fresh repo
git clone https://github.com/doubled824/EveProGlow.git
cd EveProGlow

# 2. Download the full ProGlow starter (Next.js 15 + Supabase + Stripe + Tailwind, already wired for booking + deposits + client portal)
curl -L https://github.com/evepro-glow/starter/archive/main.zip -o starter.zip
unzip starter.zip
cp -r starter-main/* .
rm -rf starter-main starter.zip

# 3. First commit — this makes it real
git add .
git commit -m "feat: initial ProGlow beauty booking stack — calendar, deposits, client portal, AI-ready"

# 4. Push it live
git push origin main
