# using

```cshrp

public class MyClientFactory: GrpcClientFactory
{
	public MyClientFactory(string grpcServiceUrl) : base(grpcServiceUrl)
	{}

	public IMyGrpcService GetMyGrpcService() => CreateGrpcService<IMyGrpcService>();
}


```




