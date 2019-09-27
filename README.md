# So you want to edit yaml in a structured way?

 * First, install lumo and js-yaml globally and set your NODE_PATH:
     ```yarn global add lumo-cljs js-yaml```
     ```export NODE_PATH=~/.config/yarn/global/node_modules```

 * Put `yaml2edn` and `edn2yaml` in your path.
     ```
     chmod a+x edn2yaml yaml2edn
     sudo cp yaml2edn edn2yaml /usr/local/bin/
     ```
 * Append `.vimrc_local` to your `.vimrc_local` if you have one, or copy it to your homedir:
     ```[[ -f ~/.vimrc_local ]] && cat .vimrc_local >> ~/.vimrc_local || cp .vimrc_local ~/```

`vim bla.yaml` and experience editing data in a structural way.  No t-square required.
