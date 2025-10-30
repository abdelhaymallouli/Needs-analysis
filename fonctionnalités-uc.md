# ⚙️ Main Features and Use Cases  

## 1. Brainstorm – All Possible Features  

### Possible Features  

- View published articles  
- Search for local initiatives (art, culture, digital projects)  
- Publish an article or story  
- Add photos to a post  
- Comment or like an article  
- Register and log in  
- View contributor profiles  
- Access through the mobile app (Android)  
- Filter by category (art, innovation, events, etc.)  

---

## 2. Prioritized Features (MoSCoW Method)

| Feature | Description | Priority |
|----------|--------------|-----------|
| Display latest articles | Homepage showing recent cultural and digital initiatives in Tangier | **Must** |
| Publish an article | Allow registered users to share local projects or initiatives | **Must** |
| Register / Login | User authentication and profile creation | **Must** |
| Comment / Like an article | Let users interact with the community | **Should** |
| Search / Filter by category | Easily find content by topic (art, culture, tech) | **Should** |
| Android mobile app | Mobile version connected through Laravel API | **Could** |


---

## 3. Use Cases (UC)

| ID | Actor | As a… | I want to… | So that I can… | Priority |
|----|--------|--------|-------------|----------------|-----------|
| UC1 | Visitor | explore recent local initiatives | discover Tangier’s creative and cultural energy | **Must** |
| UC2 | Contributor | publish an article with photos | share a local project or event | **Must** |
| UC3 | Registered user | comment and like an article | interact with the local community | **Should** |
| UC4 | User | search by category | quickly find specific topics | **Should** |

---

## 4. Use Case Diagram (Text Version)
```
         +-----------------------------------+
         |      Tangier Inspire Blog         |
         +-----------------------------------+
             /            |            \
            /             |             \
 +----------------+ +----------------+ +----------------+
 |  View Articles | | Publish Article| | Comment / Like |
 +----------------+ +----------------+ +----------------+
         |                  |                  |
      [Visitor]         [Contributor]       [User]