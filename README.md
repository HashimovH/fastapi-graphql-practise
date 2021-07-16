mutation CreateNewPost{ createNewPost(title:"new title1", content:"new content") { ok } }

query{ allPosts{ title } }

query{ postById(postId:2){ id title content } }