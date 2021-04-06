# Create an Azure Resource Group with PowerShell

Run the following commands in PowerShell to create an Azure Resource Group

```PowerShell
# Replace the following required Azure Resource Group variables
$rg = @{
    Name = 'your-rg-name'
    Location = 'EastUS2'
}

# Create an Azure ResourceGroup
New-AzResourceGroup @rg
```

## Notes

Display available Azure locations

```PowerShell
Get-AzLocation | Format-Table -Property Location, DisplayName
```

## Troubleshooting

## Alternatives

## Additional Resources

- [MS | Docs | New-AzResourceGroup][1]

<!-- Reference Links -->

[1]: https://docs.microsoft.com/en-us/powershell/module/az.resources/new-azresourcegroup?view=azps-5.7.0
