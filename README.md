[README.md](https://github.com/user-attachments/files/25403927/README.md)
# OneNet Chain MVP

**Revolutionary connection mapping that shows *how* you know people**

🚀 **Live Demo:** [onenetapp.com](https://onenetapp.com) (coming soon)

## What is Chain?

Chain is OneNet's signature feature - a visual interface that maps how any two people are connected through mutual friends, communities, events, or other relationships. Instead of showing random "People You May Know," Chain shows **contextual relationship paths**.

### Example Chain Paths:
- **Jake → David via Alex**: "College friends → Tech colleagues" 
- **Jake → Mike via Maria**: "Miami Tech Meetup → Nightlife scene"
- **Connection strength**: 8/10 (College friends) → 6/10 (Professional)

## Key Features ✨

- 🔗 **Interactive network visualization** with D3.js force-directed graphs
- 📍 **Connection path calculation** showing degrees of separation
- 💪 **Relationship strength indicators** (1-10 scale with visual thickness)
- 🎯 **Context preservation** ("Met at Miami Tech Meetup", "College friends")
- 📱 **Mobile-responsive** Chain exploration
- 🎨 **Color-coded relationship types** (friends, colleagues, family, etc.)
- ✅ **Verification badges** for trusted users
- 📊 **Network statistics** and mutual connection counts

## Live Demo

Try the interactive demo:
1. **Click on David Kim (VC)** to see path via Alex or Maria
2. **Click on Mike Johnson** to explore Miami nightlife connections  
3. **Drag users around** to visualize the network
4. **Notice connection strength** (line thickness = relationship quality)

## Technology Stack

- **Frontend**: Next.js 15, React 18, TypeScript
- **Visualization**: D3.js for interactive network graphs
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Deployment**: Vercel

## What Makes This Different

| Traditional Social Apps | OneNet Chain |
|-------------------------|--------------|
| "People You May Know" | "Jake → David via Alex" |
| Random algorithmic suggestions | Explicit connection paths |
| Binary connections (friend/not friend) | Weighted relationships (1-10 strength) |
| No relationship context | Full context ("College friends → Tech colleagues") |

## The OneNet Vision

Chain is the core of OneNet's revolutionary approach to social networking:

- **Verified identity** (one person = one account)
- **Multiple pages** (Social, Creator, Business, Student) 
- **Connection-based discovery** (navigate through relationships)
- **Trust-native commerce** (social proof built into marketplace)
- **Event-centric networking** (real-world meetups drive connections)

## Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production  
npm run build
```

## Deployment

This MVP is optimized for Vercel deployment with automatic Next.js detection.

## Future Roadmap

- [ ] Real-time Chain updates with WebSockets
- [ ] Neo4j graph database integration
- [ ] "Who should I meet?" AI discovery
- [ ] Event attendee Chain mapping
- [ ] Mobile React Native app
- [ ] Community and marketplace Chain integration

---

*OneNet: The social operating system that unifies identity, relationships, content, communities, events, and commerce through the power of Chain.*
