Setting run cmd -> .csproj
#build tailwind css mode dev

```
<Target Name="Tailwind" BeforeTargets="Build">
       <Exec Command="npm run start" />
 </Target>
 ```
  
#build tailwind css mode production

```
<Target Name="Tailwind" BeforeTargets="BeforePublish">
	<Exec Command="npm run build" />
</Target>
```
