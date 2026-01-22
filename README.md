# PB Connect

**Connecting Planetary Biology Researchers Across Sweden**

A prototype web platform for facilitating collaboration, expertise-sharing, and networking among Planetary Biology researchers in Sweden. Think "scientific Tinder" - matching researchers based on complementary expertise and collaboration needs.

🔗 **Live Prototype:** [https://olgavp-pb.github.io/PBConnect/](https://olgavp-pb.github.io/PBConnect/)

---

## 🎯 Purpose

The Planetary Biology community in Sweden spans multiple universities and disciplines. Finding the right collaborator, locating specific expertise, or building grant consortia often relies on chance encounters at conferences or existing networks. **PB Connect** aims to make these connections systematic, inclusive, and efficient.

### Problems We're Solving:
- Researchers don't know who's working on related topics at other institutions
- Finding collaborators with complementary expertise is time-consuming
- Building diverse grant consortia requires extensive networking
- Early-career researchers lack established networks
- Cross-disciplinary collaboration opportunities are missed

---

## ✨ Features (Prototype)

### 🔬 Researcher Profiles
- University affiliation (Swedish .se domains)
- Research interests and expertise
- ORCID integration
- Current projects
- What they're looking for (collaborators, expertise, grant partners, feedback)

### 🎴 Discovery Modes

**Swipe Mode:**
- Tinder-style interface for serendipitous discovery
- Quick browsing through researcher profiles
- Mutual interest creates a match

**Search Mode:**
- Filter by institution, expertise, collaboration needs
- Browse comprehensive profiles
- Direct connection requests

### 🤝 Matching System
- Matches based on mutual interest
- Reveals full contact information after matching
- Email-based communication (no in-app messaging)
- ORCID profile linking

---

## 🚧 Current Status: **Prototype**

This is a **functional prototype** demonstrating the concept and user experience. It includes:
- ✅ Working UI/UX flow
- ✅ Mock researcher profiles
- ✅ Swipe and search functionality
- ✅ Match simulation
- ❌ No real database (profiles are hardcoded)
- ❌ No authentication system
- ❌ No actual matching algorithm
- ❌ Not GDPR compliant yet

**Purpose:** Gather feedback, demonstrate concept, secure institutional support

---

## 🎯 Target Audience

**Phase 1 (Current Focus):** Planetary Biology researchers in Sweden
- SciLifeLab Planetary Biology Capability members
- Uppsala University, Lund University, Stockholm University, etc.
- ~50-100 researchers for pilot

**Phase 2 (Future):** Could expand to:
- All biodiversity/genomics researchers in Sweden
- Nordic countries
- European biodiversity networks (ERGA, BGE, etc.)

---

## 🔐 GDPR & Privacy Considerations

### Current Prototype:
- No personal data is stored
- All profiles are mock/demo data
- No tracking or analytics

### Production Requirements:
**Must Have:**
- ✅ Explicit user consent for profile visibility
- ✅ Right to be forgotten (account deletion)
- ✅ Data minimization (only collect what's necessary)
- ✅ EU/Swedish server hosting
- ✅ Privacy policy and terms of service
- ✅ Email verification for .se domains only
- ✅ Encrypted data storage
- ✅ Data export functionality
- ✅ Consent tracking and audit logs

**Privacy by Design:**
- Limited profile information before matching
- Full details only revealed after mutual interest
- No public profiles (visible only to verified users)
- Email-based communication (no in-app chat = less stored data)

---

## 🛠 Technical Requirements (Production)

### Backend Infrastructure Needed:
1. **Database** 
   - User profiles (name, email, institution, research interests)
   - Match records
   - Consent tracking
   - Must be hosted in EU/Sweden

2. **Authentication System**
   - Email verification (Swedish .se domains)
   - Secure login
   - Password recovery

3. **Matching Algorithm**
   - Track swipes/interests
   - Create matches on mutual interest
   - Notification system

4. **Email Service**
   - Match notifications
   - Contact information exchange

5. **API Integrations**
   - ORCID API for publication data
   - University email domain validation

### Technology Stack Options:

**Option A: Quick Pilot (Weeks)**
- Supabase or Firebase (with EU region)
- Pre-built authentication
- Quick to deploy
- Good for 50-100 users
- Lower cost

**Option B: Institutional Hosting (Months)**
- SciLifeLab infrastructure
- Full control over data
- Better GDPR compliance
- Requires IT department involvement
- More robust for scaling

**Option C: Commercial Platform (Days-Weeks)**
- Use existing research networking platforms
- Customize for PB community
- Faster deployment
- Ongoing costs

---

## 📊 Use Cases

### Primary Use Cases:

**1. Finding Collaborators**
- "I'm studying forest soil microbiomes and need expertise in metagenomics"
- "Looking for partners from different institutions for an EU grant"

**2. Expertise Discovery**
- "Who in Sweden works on coral reef genomics?"
- "I need feedback on my tree phylogenetics methods"

**3. Grant Consortium Building**
- "Building a Horizon Europe proposal, need partners in marine biology"
- "VR application requires multi-institutional team"

**4. Networking & Community Building**
- New postdocs finding their community
- Cross-disciplinary connections (e.g., genomics + ecology + bioinformatics)
- Establishing Swedish Planetary Biology network identity

---

## 🚀 Roadmap

### Phase 1: Validation (Current)
- ✅ Build prototype
- ⏳ Gather feedback from researchers
- ⏳ Present to SciLifeLab leadership
- ⏳ Consult with IT/Data Center
- ⏳ Assess GDPR requirements

### Phase 2: Pilot Development (If Greenlit)
- Secure institutional support/resources
- Choose technical platform
- Implement authentication & database
- GDPR compliance review
- Beta testing with 20-30 researchers

### Phase 3: Launch (If Pilot Succeeds)
- Full Swedish PB community rollout
- Onboard 50-100 researchers
- Gather usage data and feedback
- Iterate on features

### Phase 4: Expansion (Future)
- Additional features (project boards, event integration)
- Expand beyond Sweden
- Integration with other research platforms

---

## 💡 Future Features (Post-Launch)

Based on researcher needs, could add:
- **Project Boards** - Post specific collaboration opportunities
- **Skills Tags** - Searchable expertise database
- **Event Integration** - Connect around conferences/workshops
- **Research Group Profiles** - Not just individuals
- **Announcement Feed** - Share opportunities, papers, positions
- **Advanced Filters** - By career stage, techniques, organisms, etc.
- **Success Stories** - Showcase collaborations that resulted

---

## 👥 Development Team

**Concept & Design:** Olga Vinnere Pettersson (SciLifeLab, Uppsala University)  
**Technical Development:** Built with assistance from Claude AI (Anthropic)

**Institutional Context:**
- SciLifeLab Planetary Biology Capability
- Uppsala Genome Center, National Genomics Infrastructure
- European Reference Genome Atlas (ERGA)

---

## 📞 Contact & Feedback

**For Feedback or Questions:**
- GitHub Issues: [Open an issue](https://github.com/OlgaVP-PB/PBConnect/issues)
- Email: [Contact Olga Vinnere Pettersson]
- SciLifeLab Planetary Biology: [Link to capability page]

**Interested in Piloting?**
If you're a Swedish Planetary Biology researcher interested in beta testing the real version, please get in touch!

---

## 📄 License

Open source - free to use for research and education.

---

## 🙏 Acknowledgments

**Inspiration:**
- Existing research networking needs in the Planetary Biology community
- Challenges in cross-institutional collaboration
- Success of matching platforms in other domains

**Institutional Support:**
- SciLifeLab Planetary Biology Capability
- Uppsala University


---

## ⚠️ Important Notes

**This is a prototype.** It demonstrates functionality and user experience but is not production-ready. 

**No real data:** All researcher profiles in the prototype are mock data for demonstration purposes.

**Next steps require:** Institutional support, IT infrastructure, GDPR compliance review, and funding/resources for development.

---

*PB Connect - Making scientific collaboration as easy as a swipe* 🤝🔬
