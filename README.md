Frontend: [ai-electronics-hub](https://github.com/<username>/<lovable-repo-name>)


git clone https://github.com/<username>/ai-erp-graduation-project.git
cd ai-erp-graduation-project
mkdir -p workflows prompts
cp <path-to-downloaded-jsons>/*.json workflows/
cp <path-to-downloaded-prompts>/*.md prompts/
grep -ril "pat\|apikey\|secret\|token" workflows/   # בדיקת secrets לפני commit
git add .
git commit -m "Add n8n workflows, AI agent prompts, and architecture README"
git push origin main


