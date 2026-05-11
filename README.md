# Kevin's Reddit Digest Viewer

Private viewer for the reddit-digest knowledge base.

Built with: digest_to_json.py + digest_conflicts.py (in workspace/tools/)
Data source: workspace/knowledge/reddit-digest.md

## Update workflow
```bash
python3 ~/workspace/tools/digest_to_json.py
python3 ~/workspace/tools/digest_conflicts.py
cp ~/workspace/knowledge/digest_data.json ~/path/to/kevin-digest/docs/
git add docs/digest_data.json && git commit -m "digest: update YYYY-MM-DD" && git push
```
