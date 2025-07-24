Step	What It Does	Why It Matters
1. Setup	Connects to OpenAI API	Enables AI usage
2. Generate	GPT creates a workflow	Saves manual effort
3. Break	Simulates error	Mimics real-life mistakes
4. Debug	GPT auto-fixes error	Shows AI can help resolve CI issues
5. Save	Writes working file to project	Ready to run in GitHub Actions


git add .github/workflows/python-ci.yml
git commit -m "Add generated GitHub Actions workflow"
git push origin main

git add test_sample.py
git commit -m "Add sample test to ensure pytest runs"
git push origin main



GitHub Actions will now trigger the CI pipeline.

