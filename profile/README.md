We rely greatly on open source tools, and proud to contribute, too!

| Repository | Description | Release |
|-|-|-|
| [papir][1] | Design system and UI library that is explicitly **anti-chat**; it recognises that as artificial agents are becoming more and more advanced by the day, it's only becoming more obvious that the contemporary chat UI's are simply not equipped for the job. Papir borrows from literary and theatrical tradition instead, whereas our mental model is that of a _play_, or a _screenplay_. | v0.0.4 |
| [simp][2] | The _simplest_ point of consumption for LLM inference, which includes a daemon, Go library. To our knowledge, this is the only open source service to provide a fully provider-agnostic, OpenAI API-compatible Batch API interface. <br/><br/> Why is this important? <br/><br/> For example, Google Vertex AI batching is **15-50x** cheaper than competition, and it's so far the only provider to support all major media types: documents, image, audio, video. **You may submit batches using whatever models, & including providers that do not even support batching!** <br/><br/> Curiously, simp is declaratively configured with [HCL][5], akin to how _Terraform, Vault, et al._ | v0.1.0 |
| [simp.vim][4] | Vim plugin that brings simp to Vim scratch buffers, jobs, and fzf, grep-heavy workflows. Cursor has become so good, [@tucnak](https://github.com/tucnak) took it upon himself to replicate, and indeed, augment most features that you would find in Cursor, and bring them home to Vim.  | β |
| simp.vscode | Visual Studio Code extension to-be, likely a [Continue][6] fork... nobody has taken it upon themselves to do this yet, but it's glaringly obvious that it needs ot be done so I guess we would have to wait and see. | Planned |
| pg_simp | PostgreSQL extension that we use internally. This is how we're able to take on somebody with no prior programming experience, and train them to be flywheel analysts in the matter of weeks. Unfortunately, as it evolved, the internals really grew bang out of order, & open sourcing it has been a moving-goalposts type of thing. We want to get it out there, however it may take some time to stabilise. | Soon | 

Despite what news organisations would lead you to believe, the future doesn't amount to mere reshuffling or consolidation of the power structures. Think about it this way: people create, compile, share and wield information by means of storytelling. The current developments, first and foremost, have to do with this more than anything.

Our approach is inspired by the author's mastery of putting words into sentences, sentences into meanings, meanings that emerge as a result of following the rules of language games. Most notably, a language game doesn't necessarily entail dialogue how we know it; in diffusion models like Midjourney or Stable Diffusion, the prompt itself is a language-riddle being untangled by all parties: the result is a picture based solely on the description and its vibes, and leads to novel interpretations of the prompt.

To play, or not to play—that is the question.

[1]: https://github.com/busthorne/papir
[2]: https://github.com/busthorne/simp
[3]: https://github.com/busthorne/simp.vim
[4]: https://github.com/busthorne/pg_simp
[5]: https://developer.hashicorp.com/terraform/language/syntax/configuration
[6]: https://github.com/continuedev/continue
