target_sources(chcl
	PRIVATE
		BinaryFile.cpp
		BitStream.cpp
		BitStreamView.cpp
		Buffer.cpp
		JSON_Parser.cpp
		OctBool.cpp
		OctBoolArray.cpp

	PUBLIC
		FILE_SET HEADERS
		FILES
			BinaryFile.h
			BinaryHeap.h
			BitStream.h
			BitStreamView.h
			Buffer.h
			HuffmanTree.h
			JSON_Integration.h
			JSON_Parser.h
			NetworkOrder.h
			OctBool.h
			OctBoolArray.h
			QuadTree.h
)
