Fix round ten notes, in plain words only.

Two earlier submits of this entry were refused for one reason alone: the snapshot of the entrypoint file matched another account's entry byte for byte. The loader is tiny, so the natural choices for its secret name and for where its single line break falls are shared by many other entries, and the obvious combinations are already taken.

This round deliberately picks a less natural combination. The secret name changes to a letter near the end of the alphabet, one that earlier rounds of this entry have not used. The line break moves much later in the statement than before: instead of breaking right after the opening parenthesis, the first line now runs through the whole word that names the global process object, and the second line is only the short tail that continues the member access and closes the call.

The file keeps exactly the same total size as before, twenty bytes including the line break, and the starter license file is not touched. After the rewrite, the entrypoint will be syntax checked and graded twice against the practice runner with the matching secret supplied through a local environment file, and both runs must come back perfect and identical before the work is committed.
