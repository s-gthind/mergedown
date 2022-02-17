# mergedown

STEP1: CHECK IF THE PULL REQUEST IS MERGED 
 --------A) IF MERGE ACTION IS TAKEN on BRANCH merge or not
 jobs:
  test_real_event_is_merge:
    if: github.event.pull_request.merged == true
    runs-on: ubuntu-latest
    
 -------B) Triiger on branch either release_candidate oe preview
 
 
    
    
    
 
