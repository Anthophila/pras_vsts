# pras_vsts

    assert_equal false, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("r5re6wmuyil22fwl7yy7tukhtkr5dh3ex6eaw6qmtbfdikdvjlvq")
    assert_equal false, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("xwuiwqtlcznyx5ateua3232d3iq4xx2zt3dinyqyvmvk4my6ctfq")
    assert_equal false, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("advancedthreatprotectiononboardingdevicesettingstate")
    assert_equal false, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("windowsinformationprotectionpincharacterrequirements")
    
        
    
        assert_equal true, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("67csyuknm2k4azb2q3ktjb7dwnafo2xj5bwpv7vt7ei2l5a7wwfb")
    assert_equal true, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("nj3ithqqxdghjtxuo6a27lebc4ko5jyqsthyqshtnnlpvowh2oaq")
    assert_equal true, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("36tbhyubwbvmi3xzek5n7gz2mxxx3ywxoujzjoxtb3ptgdyfauia")
    assert_equal true, GitHub::TokenScanning::TokenScanningPostProcessingHelper.valid_vsts_pat_crc?("r5cd6wmuyil22fwl7yy7tukhtkr5dh3ex6eaw6qmtbfdikdvjlvq")
  
