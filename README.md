#メモ

##動画のアップロードに使用するgem⇒carrierwave
###↑使用の際は以下をモデルに記述する。↓
###mount_uploader :video, VideoUploader
###動画投稿フォーム↓
###<%= form.file_field :video %>
###動画表示↓
####<iframe width="1024" height="576" src="<%= @post.video.to_s %>" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

