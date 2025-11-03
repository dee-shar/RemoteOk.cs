# RemoteOk.cs
Web-API for [remoteok.com](https://remoteok.com/) the #1 remote jobs board in the world trusted by millions of remote workers and companies like Amazon, Microsoft, Stripe and YC

## Example
```cs
using RemoteOkApi;

namespace Application
{
    internal class Program
    {
        static async Task Main()
        {
            var api = new RemoteOk();
            string jobs = await api.GetJobs();
            Console.WriteLine(jobs);
        }
    }
}
```
