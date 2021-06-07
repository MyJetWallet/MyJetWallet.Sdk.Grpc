# using

```cshrp

public class MyClientFactory: MyGrpcClientFactory
{
	public MyClientFactory(string grpcServiceUrl) : base(grpcServiceUrl)
	{}

	public IMyGrpcService GetMyGrpcService() => CreateGrpcService<IMyGrpcService>();
}


```




