配合SdWebImage 使用，可以显示加载进度

UIImageView *imageView = [[UIImageView alloc] initWithFrame:frame];
        imageView.imageURL = attachment.contentURL;
        [imageView setOnTouchTapBlock:^(UIImageView *imageView) {
        }];
