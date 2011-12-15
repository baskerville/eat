![preview](http://f.cl.ly/items/1h430t3Y1u1t0h352l2O/eat_logo.jpg)

    SYNOPSIS
        eat <action> [arguments]

    ACTIONS 
        list
            Output a list of all the shares and files.

        add [TITLE]
            Make a new share.

        change SHARENAME TITLE
            Change the title of the share SHARENAME to TITLE. 

        remove SHARENAME
            Remove the share SHARENAME.

        show SHARENAME
            Show informations regarding the share SHARENAME.

        search PATTERN
            Search for shares whose title matches PATTERN.

        upload SHARENAME FILE ...
            Upload the given files to the share SHARENAME.

        delete SHARENAME FILEID
            Delete the file FILEID of the share SHARENAME.

        info SHARENAME FILEID
            Give informations on the file FILEID of the share SHARENAME.

        find PATTERN
            Search for files whose file name matches PATTERN.

        blob SHARENAME FILEID
            Returns the URL of the content of the file FILEID of the share SHARENAME.

        thumb SHARENAME FILEID
            Returns the URL of the content of the thumbnail of the file FILEID of the share SHARENAME.

## Configuration

Create a `~/.eatrc`:

    apikey = one
    email = two@three.four
    password = five
