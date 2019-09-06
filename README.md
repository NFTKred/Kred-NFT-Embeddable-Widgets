# Embedding NFT.Kred Widgets in your App

This guide shows how you to embed NFT.Kred widgets in your App.

## List of Widgets:
1. [NFT](#nft)
      1. [Front](#nft-front)
      2. [Back](#nft-back)
      3. [Front and Back](#nft-frontback)
      4. [Preview](#nft-preview)
3. [NFT Gallery](#gallery)
    1. [All NFTs](#gallery-all)
    2. [User's NFTs](#gallery-user)
4. [Newsfeed](#newsfeeed)

## <a name="nft"></a>NFT
Embed an NFT

### <a name="nft-front"></a>Front
Embed the front of an NFT
```html
<iframe src="https://app.nft.kred/embed/front/coin/COINID/size/SIZE"></iframe>

COINID - (int) NFT Coin ID
SIZE - (int) Width of embed image

eg. <iframe src="https://app.nft.kred/embed/front/coin/8222/size/300"></iframe>
```

<img src="http://d30p8ypma69uhv.cloudfront.net/branding/superdog-front.JPG" height="200">

### <a name="nft-back"></a>Back
Embed the back of an NFT
```html
<iframe src="https://app.nft.kred/embed/back/coin/COINID/size/SIZE"></iframe>

COINID - (int) NFT Coin ID
SIZE - (int) Width of embed image

eg. <iframe src="https://app.nft.kred/embed/back/coin/8222/size/300"></iframe>
```

<img src="http://d30p8ypma69uhv.cloudfront.net/branding/superdog-back.JPG" height="200">

### <a name="nft-frontback"></a>Front and Back
Embed both sides of an NFT
```html
<iframe src="https://app.nft.kred/embed/coin/COINID/size/SIZE"></iframe>

COINID - (int) NFT Coin ID
SIZE - (int) Width of embed image

eg. <iframe src="https://app.nft.kred/embed/coin/8222/size/300"></iframe>
```

<img src="http://d30p8ypma69uhv.cloudfront.net/branding/superdog-both.JPG" height="200">

### <a name="nft-preview"></a>Preview
Embed preview of an NFT
```html
<iframe src="https://app.nft.kred/embed/social/coin/COINID"></iframe>

COINID - (int) NFT Coin ID

eg. <iframe src="https://app.nft.kred/embed/social/coin/8222/size/300"></iframe>
```
<img src="http://d30p8ypma69uhv.cloudfront.net/branding/superdog-preview.JPG" height="200">

## <a name="gallery"></a>NFT Gallery
Embed an NFT Gallery

### <a name="gallery-all"></a>All NFTs
Embed gallery with all NFTs
```html
<iframe src="https://app.nft.kred/coingallery/SIZE"></iframe>

SIZE - (int) Width of embed image

eg. <iframe src="https://app.nft.kred/coingallery/300"></iframe>
```

### <a name="gallery-user"></a>User's NFTs
Embed gallery with a User's NFTs
```html
<iframe src="https://app.nft.kred/coingallery/USERID/SIZE"></iframe>

USERID - (string) User ID
SIZE - (int) Width of embed image

eg. <iframe src="https://app.nft.kred/coingallery/53756175b7725d370d9a208f/300"></iframe>
```

## <a name="newsfeed"></a>Newsfeed
Embed a newsfeed

```html
<iframe src="https://app.nft.kred/embed/newsfeed/collection.USERID.grab"></iframe>

USERID - (string) User ID

eg. <iframe src="https://app.nft.kred/embed/newsfeed/collection.53756175b7725d370d9a208f.grab"></iframe>
```
<img src="http://d30p8ypma69uhv.cloudfront.net/branding/newsfeed.JPG" height="350">
