# Job Search Prompt

## Objective
Create a job search summary for a candidate based on their supporting documents.

## Steps
1. Read the supporting docs: `CV/`, `Papers/`, and `Teaching_Evaluations/` to understand the candidate's interests, expertise, and academic domain.
2. Connect to MCP servers and navigate to: https://www.mathjobs.org/jobs/list
3. Filter the jobs that fit the candidate's interests and domain.
4. Output a file named `job_list_summary.md` containing a list of the filtered positions, and include the required application documents for each position.

## Output Format
The `job_list_summary.md` file should include, for each filtered job:
- HTML link
- Job title
- Brief summary
- Location
- Company or university name
- Required application documents

## Notes
- Use the candidate's CV, papers, and teaching evaluations to infer the best fit.
- Prefer academic or research positions aligned with the candidate's qualifications.
- Keep the summary concise and well-structured.
