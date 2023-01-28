# Frequency-Reuse
the Python code for visualizing the Frequency Reuse concept


<article>
Frequency Reuse is the scheme in which allocation and reuse of channels throughout a coverage region is done. Each cellular base station is allocated a group of radio channels or Frequency sub-bands to be used within a small geographic area known as a cell. The shape of the cell is Hexagonal. The process of selecting and allocating the frequency sub-bands for all of the cellular base station within a system is called Frequency reuse or Frequency Planning.
</article>


![image](https://user-images.githubusercontent.com/79093527/215267895-8b674082-7dfd-4541-9c56-a7890e0d51f7.png)


<code>
Cell with the same letter uses the same set of channels group or frequencies sub-band.
To find the total number of channel allocated to a cell:

S = Total number of duplex channels available to use
k = Channels allocated to each cell (k<S)
N = Total number of cells or Cluster Size

Then Total number of channels (S) will be,
S = kN 

Frequency Reuse Factor = 1/N
In the above diagram cluster size is 7 (A,B,C,D,E,F,G) thus frequency reuse factor is 1/7.

N is the number of cells which collectively use the complete set of available frequencies is called a Cluster. The value of N is calculated by the following formula:

N = I2 + I*J + J2 
Where I,J = 0,1,2,3…
Hence, possible values of N are 1,3,4,7,9,12,13,16,19 and so on.

If a Cluster is replicated or repeated M times within the cellular system, then Capacity, C, will be,

C = MkN = MS
In Frequency reuse there are several cells that use the same set of frequencies. These cells are called Co-Channel Cells. These Co-Channel cells results in interference. So to avoid the Interference cells that use the same set of channels or frequencies are separated from one another by a larger distance. The distance between any two Co-Channels can be calculated by the following formula:

 D = R * (3 * N)1/2
Where,
R = Radius of a cell
N = Number of cells in a given cluster
</code>
