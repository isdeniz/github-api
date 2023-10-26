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
**preprocess:** text - preprocessed version of the text including the following operations: lowercase, remove punctuations, apostropes, numbers, whitespaces, english stopwords, transform into stemmed words \
**logistic_regression:** dataset as pandas df, columns to be used in the prediction, target variable which will be predicted - confusion matrix, classification report, accuracy of the Logistic Regression classifier
