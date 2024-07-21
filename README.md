# MDGPrivateSpecs

This is a Private Specs repository created to access MyDogsGallery (https://github.com/kapilkhedkar/MyDogsGallery) framework in the iOS application PawPics (https://github.com/kapilkhedkar/PawPics). 

## Why Private Specs repository?
Ideally, one should publish the Framework to Cocoapods and then directly use it like a normal pod in your application by mentioning it in the Podfile. I did manage to upload the framework to Cocoapods (Proof:- https://cocoapods.org/pods/MyDogsGallery).

However, sometimes it takes time for the Cocoapods central depository to reflect updates and thus I needed an alternative option to use my framework in PawPics. Thus, I uploaded my framework's podspec file to this Private Specs repository and mentioned it in the podfile of PawPics. With that done, I could easily access my framework without waiting for Cocoapods central depository updates.
