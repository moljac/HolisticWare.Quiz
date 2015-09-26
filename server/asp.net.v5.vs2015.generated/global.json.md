{
//System.InvalidOperationException: No service for type 'Microsoft.Framework.Runtime.IApplicationEnvironment' has been registered.
//  at Microsoft.Framework.DependencyInjection.ServiceProviderExtensions.GetRequiredService (IServiceProvider provider, System.Type serviceType) [0x00000] in <filename unknown>:0 
//  at Microsoft.Framework.DependencyInjection.ServiceProviderExtensions.GetRequiredService[IApplicationEnvironment] (IServiceProvider provider) [0x00000] in <filename unknown>:0 
//  at Microsoft.AspNet.Hosting.Program.Main (System.String[] args) [0x00000] in <filename unknown>:0 
//  at (wrapper managed-to-native) System.Reflection.MonoMethod:InternalInvoke (System.Reflection.MonoMethod,object,object[],System.Exception&)
//  at System.Reflection.MonoMethod.Invoke (System.Object obj, BindingFlags invokeAttr, System.Reflection.Binder binder, System.Object[] parameters, System.Globalization.CultureInfo culture) [0x00000] in <filename unknown>:0 
//--- End of stack trace from previous location where exception was thrown ---
//  at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw () [0x00000] in <filename unknown>:0 
//  at Microsoft.Dnx.Runtime.Common.EntryPointExecutor.Execute (System.Reflection.Assembly assembly, System.String[] args, IServiceProvider serviceProvider) [0x00000] in <filename unknown>:0 
//  at Microsoft.Dnx.ApplicationHost.Program.ExecuteMain (Microsoft.Dnx.Runtime.DefaultHost host, System.String applicationName, System.String[] args) [0x00000] in <filename unknown>:0 
//  at Microsoft.Dnx.ApplicationHost.Program.Main (System.String[] args) [0x00000] in <filename unknown>:0 
//--- End of stack trace from previous location where exception was thrown ---
//  at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw () [0x00000] in <filename unknown>:0 
//  at Microsoft.Dnx.Runtime.Common.EntryPointExecutor.Execute (System.Reflection.Assembly assembly, System.String[] args, IServiceProvider serviceProvider) [0x00000] in <filename unknown>:0 
//  at Microsoft.Dnx.Host.Bootstrapper.RunAsync (System.Collections.Generic.List`1 args, IRuntimeEnvironment env, System.Runtime.Versioning.FrameworkName targetFramework) [0x00000] in <filename unknown>:0 
//
//    "projects": 
//		[ 
//			"src" 
//		],
    "sdk": 
	{
        "version": "1.0.0-beta4"
    }
}