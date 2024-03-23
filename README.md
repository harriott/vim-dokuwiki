vim: fdl=3:

# vim-dokuwiki

## about this fork
This is my fork of the excellent [vim-dokuwiki](https://github.com/nblock/vim-dokuwiki).

I've just make a few changes to [$vfp/packs-cp/opt/vim-dokuwiki/syntax/dokuwiki.vim](https://github.com/harriott/vim-dokuwiki/blob/master/syntax/dokuwiki.vim).

## merging from nblock upstream

    git remote add upstream https://github.com/nblock/vim-dokuwiki
    git remote -v                                # check remote locations
    git fetch upstream                           # grab the changed upstream
    git merge upstream/master -m 'merge message' # merges in the changes
    rg HEAD                                      # ripgrep for any conflicts
    in vim: /^<<<<<<< HEAD$\|^=======$\|^>>>>>>> upstream/master$
    gic '1 commit behind'
    git merge --abort                            # undo the merge



