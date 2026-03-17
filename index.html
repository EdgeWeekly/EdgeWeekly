import { useState } from "react";

const TABS = ["🏀 Overview", "📅 Content Calendar", "📧 Newsletter", "💰 Monetization", "🤝 Alex's Role"];

const SPORTS = [
  {
    name: "NFL", icon: "🏈", color: "#1d4ed8", season: "Sep–Feb",
    content: ["Weekly model picks", "Line movement alerts", "Injury impact analysis", "Sharp vs public money", "Fantasy streaming picks"],
    topics: ["Best bets Week 1–18", "Fantasy waiver wire", "Playoff bracket picks", "Super Bowl model"],
  },
  {
    name: "NBA", icon: "🏀", color: "#dc2626", season: "Oct–Jun",
    content: ["Player prop edges", "Game spread picks", "Pace & efficiency matchups", "Playoff upset alerts", "Fantasy daily picks"],
    topics: ["In-season tournament edges", "Trade deadline impact", "Playoff model picks", "Championship odds"],
  },
  {
    name: "MLB", icon: "⚾", color: "#16a34a", season: "Apr–Oct",
    content: ["Pitcher matchup edges", "Team total picks", "Bullpen efficiency", "Weather impact model", "Fantasy streamers"],
    topics: ["Opening day picks", "Division race model", "Playoff upset alerts", "World Series model"],
  },
  {
    name: "NCAAB", icon: "🏀", color: "#f97316", season: "Nov–Apr",
    content: ["Barttorvik efficiency picks", "Upset alerts", "Pool leverage scores", "Bracket strategy", "Conference tournament picks"],
    topics: ["March Madness bracket", "Upset alerts", "Final Four model", "Championship pick"],
  },
];

const CALENDAR = [
  { month: "March", sport: "NCAAB + NBA", focus: "March Madness + NBA stretch run", picks: "Bracket upsets, NBA playoff race edges", color: "#f97316" },
  { month: "April", sport: "NBA + MLB", focus: "NBA playoffs begin + MLB opening", picks: "First round NBA upsets, early MLB inefficiencies", color: "#dc2626" },
  { month: "May", sport: "NBA + MLB", focus: "Conference finals + MLB pace data", picks: "Conference finals model picks, MLB team totals", color: "#16a34a" },
  { month: "June", sport: "NBA + MLB", focus: "NBA Finals + MLB summer", picks: "Finals model, MLB division leaders", color: "#1d4ed8" },
  { month: "July", sport: "MLB + NFL", focus: "MLB All-Star break + NFL preseason", picks: "MLB second half picks, NFL early market edges", color: "#8b5cf6" },
  { month: "August", sport: "NFL + MLB", focus: "NFL preseason + MLB playoff race", picks: "NFL position battle impacts, MLB wild card model", color: "#f59e0b" },
  { month: "September", sport: "NFL + MLB", focus: "NFL Week 1 + MLB playoffs", picks: "NFL opening lines, MLB playoff bracket", color: "#dc2626" },
  { month: "October", sport: "NFL + MLB", focus: "NFL + World Series", picks: "NFL weekly picks, World Series model", color: "#16a34a" },
  { month: "November", sport: "NFL + NCAAB", focus: "NFL + College hoops start", picks: "NFL playoff picture, early NCAAB efficiency", color: "#1d4ed8" },
  { month: "December", sport: "NFL + NCAAB", focus: "NFL playoff race + Bowl season", picks: "NFL wild card picture, bowl game model", color: "#f97316" },
];

const NEWSLETTER = {
  free: [
    "1 best bet of the week",
    "Top upset alert",
    "One team breakdown",
    "Model leaderboard update",
  ],
  paid: [
    "5-8 picks across all sports",
    "Full model breakdowns",
    "Injury impact analysis",
    "Sharp vs public breakdown",
    "Fantasy streaming picks",
    "Line movement alerts",
    "Pool/parlay strategy",
    "Direct access to ask questions",
  ],
};

const REVENUE = [
  { stream: "Newsletter — Paid tier", price: "$7/mo", when: "Month 1", note: "Beehiiv free, starts immediately" },
  { stream: "Bracket Package PDF", price: "$4.99 one-time", when: "This week", note: "March Madness impulse buy" },
  { stream: "Full Season Pass", price: "$49 one-time", when: "Month 2", note: "NFL + NBA + MLB full year access" },
  { stream: "Whop subscription", price: "$19/mo", when: "Now", note: "Already live on metricsmadness.netlify.app" },
  { stream: "DraftKings affiliate", price: "$200-500/signup", when: "Week 2", note: "Per referred bettor" },
  { stream: "Fantasy advice tier", price: "$12/mo", when: "Month 3", note: "Separate fantasy-focused tier" },
];

export default function App() {
  const [tab, setTab] = useState(0);
  const [openSport, setOpenSport] = useState(null);

  return (
    <div style={{ background: "#07091a", minHeight: "100vh", fontFamily: "system-ui,sans-serif", color: "#e2e8f0", fontSize: 13 }}>

      {/* Header */}
      <div style={{ background: "linear-gradient(135deg,#0f1535,#07091a)", borderBottom: "1px solid #1e2d50", padding: "16px 20px 0" }}>
        <div style={{ maxWidth: 900, margin: "0 auto" }}>
          <div style={{ marginBottom: 10 }}>
            <div style={{ fontSize: 22, fontWeight: 800, background: "linear-gradient(90deg,#f97316,#facc15)", WebkitBackgroundClip: "text", WebkitTextFillColor: "transparent" }}>Edge Weekly</div>
            <div style={{ fontSize: 11, color: "#64748b", marginTop: 2 }}>by Madness Metrics · NFL · NBA · MLB · NCAAB</div>
          </div>
          <div style={{ display: "flex", gap: 1, overflowX: "auto" }}>
            {TABS.map((t, i) => (
              <button key={t} onClick={() => setTab(i)} style={{ background: tab === i ? "#0f1535" : "transparent", border: "none", borderBottom: tab === i ? "2px solid #f97316" : "2px solid transparent", padding: "7px 12px", color: tab === i ? "#f97316" : "#64748b", fontWeight: tab === i ? 700 : 400, fontSize: 11, cursor: "pointer", whiteSpace: "nowrap" }}>{t}</button>
            ))}
          </div>
        </div>
      </div>

      <div style={{ maxWidth: 900, margin: "0 auto", padding: 20 }}>

        {/* TAB 0 — OVERVIEW */}
        {tab === 0 && (
          <div>
            <div style={{ fontSize: 12, color: "#94a3b8", marginBottom: 16 }}>One brand. Four sports. Year-round content and revenue.</div>

            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 10, marginBottom: 16 }}>
              {SPORTS.map(s => (
                <div key={s.name} onClick={() => setOpenSport(openSport === s.name ? null : s.name)}
                  style={{ background: "#0f1535", border: `1px solid ${openSport === s.name ? s.color : "#1e2d50"}`, borderRadius: 12, padding: 14, cursor: "pointer" }}>
                  <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 6 }}>
                    <div style={{ fontWeight: 800, fontSize: 15 }}>{s.icon} {s.name}</div>
                    <div style={{ fontSize: 10, color: s.color, fontWeight: 700, background: `${s.color}22`, padding: "2px 8px", borderRadius: 20 }}>{s.season}</div>
                  </div>
                  {openSport === s.name && (
                    <div style={{ marginTop: 10 }}>
                      <div style={{ fontSize: 10, color: "#64748b", textTransform: "uppercase", letterSpacing: 1, marginBottom: 6 }}>Content</div>
                      {s.content.map(c => (
                        <div key={c} style={{ display: "flex", gap: 6, marginBottom: 4, fontSize: 11, color: "#cbd5e1" }}>
                          <span style={{ color: s.color }}>→</span><span>{c}</span>
                        </div>
                      ))}
                    </div>
                  )}
                  <div style={{ fontSize: 10, color: "#64748b", marginTop: 4 }}>{openSport === s.name ? "Tap to close" : "Tap to expand"}</div>
                </div>
              ))}
            </div>

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #f97316" }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#f97316", marginBottom: 12 }}>The year-round engine</div>
              <div style={{ fontSize: 12, color: "#94a3b8", lineHeight: 1.8 }}>
                March Madness builds the audience → NBA playoffs keeps them → MLB summer grows it → NFL season monetizes it at scale. You never go dark. Every month has content. Every month has picks. Every month has revenue.
              </div>
            </div>
          </div>
        )}

        {/* TAB 1 — CALENDAR */}
        {tab === 1 && (
          <div>
            <div style={{ fontSize: 12, color: "#94a3b8", marginBottom: 16 }}>Year-round content — you never run out of material.</div>
            {CALENDAR.map((m, i) => (
              <div key={m.month} style={{ background: "#0f1535", border: `1px solid #1e2d50`, borderRadius: 10, padding: 14, marginBottom: 8, display: "flex", gap: 12, alignItems: "flex-start" }}>
                <div style={{ background: m.color, borderRadius: 8, padding: "6px 10px", minWidth: 70, textAlign: "center", flexShrink: 0 }}>
                  <div style={{ color: "#fff", fontSize: 11, fontWeight: 800 }}>{m.month}</div>
                </div>
                <div style={{ flex: 1 }}>
                  <div style={{ display: "flex", gap: 8, marginBottom: 4, flexWrap: "wrap" }}>
                    {m.sport.split(" + ").map(s => (
                      <span key={s} style={{ fontSize: 10, fontWeight: 700, color: "#facc15", background: "#1e2d50", padding: "1px 8px", borderRadius: 20 }}>{s}</span>
                    ))}
                  </div>
                  <div style={{ fontWeight: 700, fontSize: 13, marginBottom: 3 }}>{m.focus}</div>
                  <div style={{ fontSize: 11, color: "#64748b" }}>{m.picks}</div>
                </div>
              </div>
            ))}
          </div>
        )}

        {/* TAB 2 — NEWSLETTER */}
        {tab === 2 && (
          <div>
            <div style={{ fontSize: 12, color: "#94a3b8", marginBottom: 16 }}>Edge Weekly — free tier grows the list, paid tier makes money.</div>

            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 12, marginBottom: 16 }}>
              <div style={{ background: "#0f1535", border: "1px solid #1e2d50", borderRadius: 12, padding: 16 }}>
                <div style={{ fontSize: 11, color: "#64748b", fontWeight: 700, letterSpacing: 1, textTransform: "uppercase", marginBottom: 10 }}>Free Tier</div>
                <div style={{ fontSize: 20, fontWeight: 800, color: "#fff", marginBottom: 12 }}>$0</div>
                {NEWSLETTER.free.map(f => (
                  <div key={f} style={{ display: "flex", gap: 8, marginBottom: 8, fontSize: 11, color: "#cbd5e1" }}>
                    <span style={{ color: "#4ade80" }}>✓</span><span>{f}</span>
                  </div>
                ))}
              </div>
              <div style={{ background: "#0f1535", border: "1px solid #f97316", borderRadius: 12, padding: 16 }}>
                <div style={{ fontSize: 11, color: "#f97316", fontWeight: 700, letterSpacing: 1, textTransform: "uppercase", marginBottom: 10 }}>Paid Tier</div>
                <div style={{ fontSize: 20, fontWeight: 800, color: "#facc15", marginBottom: 12 }}>$7/mo</div>
                {NEWSLETTER.paid.map(f => (
                  <div key={f} style={{ display: "flex", gap: 8, marginBottom: 8, fontSize: 11, color: "#cbd5e1" }}>
                    <span style={{ color: "#f97316" }}>✓</span><span>{f}</span>
                  </div>
                ))}
              </div>
            </div>

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #1e2d50", marginBottom: 12 }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#facc15", marginBottom: 12 }}>Setup — 20 minutes</div>
              {[
                ["1", "Go to beehiiv.com → sign up free"],
                ["2", "Name: Edge Weekly by Madness Metrics"],
                ["3", "Set paid tier at $7/month"],
                ["4", "Write first issue — March Madness picks"],
                ["5", "Get subscribe link → add to every bio"],
                ["6", "End every TikTok and tweet with newsletter CTA"],
              ].map(([n, step]) => (
                <div key={n} style={{ display: "flex", gap: 10, marginBottom: 10, alignItems: "flex-start" }}>
                  <span style={{ background: "#f97316", color: "#000", fontSize: 10, fontWeight: 800, padding: "2px 8px", borderRadius: 20, flexShrink: 0 }}>{n}</span>
                  <span style={{ fontSize: 12, color: "#94a3b8", lineHeight: 1.6 }}>{step}</span>
                </div>
              ))}
            </div>

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #1e2d50" }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#facc15", marginBottom: 10 }}>Subscriber growth math</div>
              {[
                ["Month 1", "50 free · 3 paid", "$21/mo"],
                ["Month 2", "150 free · 10 paid", "$70/mo"],
                ["Month 3", "400 free · 25 paid", "$175/mo"],
                ["Month 6", "1,000 free · 60 paid", "$420/mo"],
                ["Year 1", "3,000 free · 150 paid", "$1,050/mo"],
              ].map(([period, subs, rev]) => (
                <div key={period} style={{ display: "flex", justifyContent: "space-between", alignItems: "center", padding: "8px 0", borderBottom: "1px solid #0d1224" }}>
                  <div style={{ fontSize: 12, fontWeight: 700 }}>{period}</div>
                  <div style={{ fontSize: 11, color: "#64748b" }}>{subs}</div>
                  <div style={{ fontSize: 13, fontWeight: 800, color: "#4ade80" }}>{rev}</div>
                </div>
              ))}
            </div>
          </div>
        )}

        {/* TAB 3 — MONETIZATION */}
        {tab === 3 && (
          <div>
            <div style={{ fontSize: 12, color: "#94a3b8", marginBottom: 16 }}>Stack all revenue streams. Each one adds on top of the last.</div>
            {REVENUE.map((r, i) => (
              <div key={r.stream} style={{ background: "#0f1535", border: "1px solid #1e2d50", borderRadius: 10, padding: 14, marginBottom: 8, display: "flex", justifyContent: "space-between", alignItems: "flex-start", gap: 10 }}>
                <div style={{ flex: 1 }}>
                  <div style={{ fontWeight: 700, fontSize: 13, marginBottom: 3 }}>{r.stream}</div>
                  <div style={{ fontSize: 11, color: "#64748b" }}>{r.note}</div>
                </div>
                <div style={{ textAlign: "right", flexShrink: 0 }}>
                  <div style={{ fontSize: 14, fontWeight: 800, color: "#4ade80" }}>{r.price}</div>
                  <div style={{ fontSize: 10, color: "#f97316", marginTop: 2 }}>{r.when}</div>
                </div>
              </div>
            ))}

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #f97316", marginTop: 8 }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#f97316", marginBottom: 10 }}>Realistic end of semester target</div>
              {[
                ["Newsletter 60 paid × $7", "$420/mo"],
                ["Whop 10 subscribers × $19", "$190/mo"],
                ["DraftKings affiliate 5 signups", "$1,000 one-time"],
                ["Season pass sales", "$200 one-time"],
              ].map(([label, val]) => (
                <div key={label} style={{ display: "flex", justifyContent: "space-between", padding: "6px 0", borderBottom: "1px solid #0d1224", fontSize: 12 }}>
                  <span style={{ color: "#94a3b8" }}>{label}</span>
                  <span style={{ fontWeight: 700, color: "#facc15" }}>{val}</span>
                </div>
              ))}
              <div style={{ display: "flex", justifyContent: "space-between", paddingTop: 10, fontSize: 14, fontWeight: 800 }}>
                <span style={{ color: "#fff" }}>Monthly recurring</span>
                <span style={{ color: "#4ade80" }}>~$610/mo</span>
              </div>
            </div>
          </div>
        )}

        {/* TAB 4 — ALEX */}
        {tab === 4 && (
          <div>
            <div style={{ fontSize: 12, color: "#94a3b8", marginBottom: 16 }}>Alex's role — social media manager, no equity yet, revenue share only.</div>

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #1e2d50", marginBottom: 12 }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#facc15", marginBottom: 12 }}>What Alex does</div>
              {[
                ["Content posting", "Posts all TikTok and Twitter content daily — you provide the scripts and graphics"],
                ["Social media manager", "Responds to comments, DMs, engages with community"],
                ["Ideas", "Brainstorms content angles — you approve everything"],
                ["Potentially face", "If he's willing, he films talking head videos using your scripts"],
              ].map(([role, desc]) => (
                <div key={role} style={{ marginBottom: 12, padding: "10px 12px", background: "#07091a", borderRadius: 8 }}>
                  <div style={{ fontWeight: 700, fontSize: 12, color: "#f97316", marginBottom: 3 }}>{role}</div>
                  <div style={{ fontSize: 11, color: "#94a3b8", lineHeight: 1.6 }}>{desc}</div>
                </div>
              ))}
            </div>

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #1e2d50", marginBottom: 12 }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#facc15", marginBottom: 12 }}>What Alex does NOT get</div>
              {["Equity — not yet", "Access to revenue numbers until trust is established", "Decision-making power — you run the product", "Whop login or payment access"].map(f => (
                <div key={f} style={{ display: "flex", gap: 8, marginBottom: 8, fontSize: 11, color: "#cbd5e1" }}>
                  <span style={{ color: "#f87171" }}>✗</span><span>{f}</span>
                </div>
              ))}
            </div>

            <div style={{ background: "#0f1535", borderRadius: 12, padding: 16, border: "1px solid #f97316" }}>
              <div style={{ fontSize: 12, fontWeight: 700, color: "#f97316", marginBottom: 12 }}>Deal structure to offer Alex</div>
              <div style={{ fontSize: 12, color: "#94a3b8", lineHeight: 1.8, marginBottom: 12 }}>
                Start with a handshake deal — no contracts needed yet. Tell him:
              </div>
              <div style={{ background: "#07091a", borderRadius: 8, padding: 14, fontSize: 12, color: "#cbd5e1", lineHeight: 1.8, fontStyle: "italic" }}>
                "You run social media, I run the product. Once we're making consistent money I'll give you 20% of revenue you directly drive. For now let's just build it together and see how it goes."
              </div>
            </div>
          </div>
        )}
      </div>
    </div>
  );
}
