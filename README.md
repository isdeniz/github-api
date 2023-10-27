<h3 align="center">GitHub Search API Functions</h3>

<h3 align="left">This repository contains functions written in Python to extract repository, issue, release, commit and label data with the GitHub Search API.</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


### Information about functions : input - output
**created_at:** name of the repository - creation date of the repository \
**stargazers_count:** name of the repository - number of stars given to the repository \
**watchers_count:** name of the repository - number of watchers of the repository \
**open_issue_count:** name of the repository - # of open issues (not including pull requests) the repository \
**closed_issue_count:** name of the repository - # of closed issues (not including pull requests) the repository \
**open_pr_count:** name of the repository - # of open pull requests (not including other issues that are not pull requests) the repository \
**closed_pr_count:** name of the repository - # of closed pull requests (not including other issues that are not pull requests) the repository \
**commit_count:** name of the repository - # of commits made in the repository \
**release_count:** name of the repository - # of releases made in the repository \
**issue_info:** name of the repository - issue data as df \
**pullRequest_info:** name of the repository - pull request data as df \
**label_info:** name of the repository - label data of the labels that are used in the repository as df \
**release_info:** name of the repository - release data as df \
**issue_release_tag:** release_info,name of the repository,created_at - tag of the current release of the repository when the issue was created \
**issue_release_date:** release_info,name of the repository,created_at - date of the current release of the repository when the issue was created \
**issue_release_graph:** issue_info,name of the repository - graph of the number of issues created through the releases of the repository \
