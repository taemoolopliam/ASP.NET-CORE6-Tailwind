#dev
  <Target Name="Tailwind" BeforeTargets="Build">
		<Exec Command="npm run start" />
	</Target>
  
#production
	<Target Name="Tailwind" BeforeTargets="BeforePublish">
		<Exec Command="npm run build" />
	</Target>
