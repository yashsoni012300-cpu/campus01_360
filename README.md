# Campus360
Zero-dependency project (no `npm install` needed). Static site in `public/`, serverless API in `api/`.

## Deploy
1. Push to GitHub.
2. Vercel -> Add New Project -> import repo -> Framework Preset: **Other** -> Deploy (leave all build settings empty).
3. Settings -> Environment Variables -> add `JWT_SECRET` (any long random string) -> Redeploy.
4. To make new registrations and complaints persist: Project -> Storage -> Marketplace -> **Upstash Redis** -> connect -> Redeploy.

Demo logins work immediately: student@campus360.com / Student@123 | admin@campus360.com / Admin@123
