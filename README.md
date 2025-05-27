# Photography Portfolio - Strapi CMS

Backend CMS for no bullshit photography portfolio.

## Setup

1. **Install**

```bash
npm install
```

2. **Development**

```bash
npm run develop
```

Admin panel: http://localhost:1337/admin

3. **Content Types**
   Create these in Strapi admin:

**Gallery Items**

-   `title` (Text)
-   `image` (Media - Single)
-   `tag` (Text)

**Portfolio Items**

-   `title` (Text)
-   `image` (Media - Single)
-   `description` (Text)

**Bio**

-   `title` (Text)
-   `description` (Rich Text)
-   `tags` (JSON)
-   `profileImage` (Media - Single)

4. **API Tokens**
   Settings → API Tokens → Create token with read permissions

## Deploy

```bash
npm run build
npm start
```

---

_Keep it simple. Add content. Deploy._
