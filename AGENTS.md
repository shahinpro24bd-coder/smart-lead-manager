<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->
- Serve the brand logo from public/ as a plain file, not a Lovable asset pointer, so it loads on any host.
- previous_version_leads returns only archive rows whose original user_id matches the caller; global canonical_link uniqueness on leads blocks re-adding any link from any account.

- Keep lead collection and the lead register above the overview and feature navigation; share presentation tokens in src/styles.css to keep user, sign-in and admin screens consistent.
