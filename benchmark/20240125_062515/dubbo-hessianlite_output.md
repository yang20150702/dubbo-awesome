# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
Iteration   1: 5.404 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.404 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.738 ops/ms
Iteration   1: 12.383 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.383 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ops/ms
Iteration   1: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.086 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.228 ops/ms
Iteration   1: 3.673 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.673 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.005 ±(99.9%) 0.067 ms/op
Iteration   1: 2.925 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.925 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.034 ms/op
Iteration   1: 1.818 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.047 ms/op
Iteration   1: 3.253 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.253 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.081 ±(99.9%) 0.249 ms/op
Iteration   1: 8.156 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.211 ±(99.9%) 0.098 ms/op
Iteration   1: 3.059 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   8.919 ms/op
                 createUser·p0.999:  12.577 ms/op
                 createUser·p0.9999: 14.532 ms/op
                 createUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10459
  mean =      3.059 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1278 
    [ 2.500,  3.750) = 8639 
    [ 3.750,  5.000) = 251 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      8.919 ms/op
     p(99.9000) =     12.577 ms/op
     p(99.9900) =     14.532 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ±(99.9%) 0.070 ms/op
Iteration   1: 1.797 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.289 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.327 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 20.462 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17768
  mean =      1.797 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17187 
    [ 2.500,  5.000) = 502 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.289 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     20.462 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ±(99.9%) 0.106 ms/op
Iteration   1: 2.874 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.732 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  6.535 ms/op
                 getUser·p0.9999: 7.133 ms/op
                 getUser·p1.00:   7.143 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11133
  mean =      2.874 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 30 
    [1.500, 2.000) = 220 
    [2.000, 2.500) = 3410 
    [2.500, 3.000) = 3675 
    [3.000, 3.500) = 2102 
    [3.500, 4.000) = 1097 
    [4.000, 4.500) = 346 
    [4.500, 5.000) = 61 
    [5.000, 5.500) = 104 
    [5.500, 6.000) = 54 
    [6.000, 6.500) = 21 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.732 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      6.535 ms/op
     p(99.9900) =      7.133 ms/op
     p(99.9990) =      7.143 ms/op
     p(99.9999) =      7.143 ms/op
    p(100.0000) =      7.143 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.090 ±(99.9%) 0.429 ms/op
Iteration   1: 8.390 ±(99.9%) 0.209 ms/op
                 listUser·p0.00:   3.465 ms/op
                 listUser·p0.50:   7.766 ms/op
                 listUser·p0.90:   11.043 ms/op
                 listUser·p0.95:   12.399 ms/op
                 listUser·p0.99:   23.293 ms/op
                 listUser·p0.999:  47.792 ms/op
                 listUser·p0.9999: 49.480 ms/op
                 listUser·p1.00:   49.480 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3821
  mean =      8.390 ±(99.9%) 0.209 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 135 
    [ 5.000, 10.000) = 3064 
    [10.000, 15.000) = 543 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      3.465 ms/op
     p(50.0000) =      7.766 ms/op
     p(90.0000) =     11.043 ms/op
     p(95.0000) =     12.399 ms/op
     p(99.0000) =     23.293 ms/op
     p(99.9000) =     47.792 ms/op
     p(99.9900) =     49.480 ms/op
     p(99.9990) =     49.480 ms/op
     p(99.9999) =     49.480 ms/op
    p(100.0000) =     49.480 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.404          ops/ms
Client.existUser                       thrpt         12.383          ops/ms
Client.getUser                         thrpt          8.086          ops/ms
Client.listUser                        thrpt          3.673          ops/ms
Client.createUser                       avgt          2.925           ms/op
Client.existUser                        avgt          1.818           ms/op
Client.getUser                          avgt          3.253           ms/op
Client.listUser                         avgt          8.156           ms/op
Client.createUser                     sample  10459   3.059 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.290           ms/op
Client.createUser:createUser·p0.50    sample          2.904           ms/op
Client.createUser:createUser·p0.90    sample          3.424           ms/op
Client.createUser:createUser·p0.95    sample          3.813           ms/op
Client.createUser:createUser·p0.99    sample          8.919           ms/op
Client.createUser:createUser·p0.999   sample         12.577           ms/op
Client.createUser:createUser·p0.9999  sample         14.532           ms/op
Client.createUser:createUser·p1.00    sample         14.533           ms/op
Client.existUser                      sample  17768   1.797 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.289           ms/op
Client.existUser:existUser·p0.50      sample          1.702           ms/op
Client.existUser:existUser·p0.90      sample          2.122           ms/op
Client.existUser:existUser·p0.95      sample          2.327           ms/op
Client.existUser:existUser·p0.99      sample          3.690           ms/op
Client.existUser:existUser·p0.999     sample         20.283           ms/op
Client.existUser:existUser·p0.9999    sample         20.462           ms/op
Client.existUser:existUser·p1.00      sample         20.513           ms/op
Client.getUser                        sample  11133   2.874 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.796           ms/op
Client.getUser:getUser·p0.50          sample          2.732           ms/op
Client.getUser:getUser·p0.90          sample          3.650           ms/op
Client.getUser:getUser·p0.95          sample          4.059           ms/op
Client.getUser:getUser·p0.99          sample          5.423           ms/op
Client.getUser:getUser·p0.999         sample          6.535           ms/op
Client.getUser:getUser·p0.9999        sample          7.133           ms/op
Client.getUser:getUser·p1.00          sample          7.143           ms/op
Client.listUser                       sample   3821   8.390 ± 0.209   ms/op
Client.listUser:listUser·p0.00        sample          3.465           ms/op
Client.listUser:listUser·p0.50        sample          7.766           ms/op
Client.listUser:listUser·p0.90        sample         11.043           ms/op
Client.listUser:listUser·p0.95        sample         12.399           ms/op
Client.listUser:listUser·p0.99        sample         23.293           ms/op
Client.listUser:listUser·p0.999       sample         47.792           ms/op
Client.listUser:listUser·p0.9999      sample         49.480           ms/op
Client.listUser:listUser·p1.00        sample         49.480           ms/op
