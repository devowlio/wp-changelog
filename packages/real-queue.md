# real-queue

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.2.0 (2021-07-20)


### feat

* add new checklist item to scan the website (CU-mk8ec0)
* allow to fetch queue status and delete jobs by type (CU-m57phr)
* automatically rescan updated posts
* initial commit with working server-worker queue (CU-kh49jp)
* introduce client worker and localStorage restore functionality (CU-kh49jp)
* introduce new event to modify job delay depending on idle state
* introduce new JobDone event
* prepare new functionalities for the initial release (CU-kh49jp)


### fix

* automatically refresh jobs if queue is empty and there are still remaining items
* be more loose when getting and parsing the sitemap
* do not add duplicate URLs to queue
* do not enqueue real-queue on frontend for logged-in users
* localStorage per WordPress instance to be MU compatible
* only run one queue per browser session
* review 1 (CU-mtdp7v, CU-n1f1xc)
* review 2 (CU-7mvhak)
* review user tests #2 (CU-nvafz0)
* tab locking did not work as expected and introduced worker notifications


### perf

* speed up scan process by reducing server requests (CU-nvafz0)
