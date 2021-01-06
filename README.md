# Android Viewbinding delegated property 

With this library you can use the power of kotlin delegated properties and easily delegate your viewbinding classes.
One of the advantages of this library is the reduction of your code.

![alt text](https://uupload.ir/files/89dr_1_mbgf3jidykv-5_b_dsnr8g_(1).png)
## installation (Gradle)

Add this line in your build.gradle file :

```gradle
dependencies {
	        implementation 'com.github.A-Azizi79:Android-ViewBindingDelegatedProperty-kotlin:0.1.0'
	}
```

## Usage

```kotlin
    val binding: YourActivityNameBinding by viewBinding(YourActivityNameBinding::inflate)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
