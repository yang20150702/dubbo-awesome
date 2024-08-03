# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.824 ops/ms
Iteration   1: 5.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.374 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ops/ms
Iteration   1: 12.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.455 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.564 ops/ms
Iteration   1: 10.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.436 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ops/ms
Iteration   1: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.389 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ±(99.9%) 0.097 ms/op
Iteration   1: 2.229 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.009 ±(99.9%) 0.049 ms/op
Iteration   1: 1.875 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.064 ms/op
Iteration   1: 1.990 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ±(99.9%) 0.105 ms/op
Iteration   1: 3.668 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.668 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ±(99.9%) 0.086 ms/op
Iteration   1: 2.200 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   6.460 ms/op
                 createUser·p0.999:  34.895 ms/op
                 createUser·p0.9999: 35.854 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14537
  mean =      2.200 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12340 
    [ 2.500,  5.000) = 1965 
    [ 5.000,  7.500) = 127 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      6.460 ms/op
     p(99.9000) =     34.895 ms/op
     p(99.9900) =     35.854 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.089 ±(99.9%) 0.077 ms/op
Iteration   1: 1.763 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.285 ms/op
                 existUser·p0.50:   1.608 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.587 ms/op
                 existUser·p0.999:  24.988 ms/op
                 existUser·p0.9999: 25.768 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18141
  mean =      1.763 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16973 
    [ 2.500,  5.000) = 1072 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.587 ms/op
     p(99.9000) =     24.988 ms/op
     p(99.9900) =     25.768 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.024 ±(99.9%) 0.072 ms/op
Iteration   1: 1.905 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   1.714 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.948 ms/op
                 getUser·p0.999:  12.340 ms/op
                 getUser·p0.9999: 13.039 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16811
  mean =      1.905 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 15069 
    [ 2.500,  3.750) = 1429 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.948 ms/op
     p(99.9000) =     12.340 ms/op
     p(99.9900) =     13.039 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.111 ms/op
Iteration   1: 3.147 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.153 ms/op
                 listUser·p0.999:  7.906 ms/op
                 listUser·p0.9999: 8.417 ms/op
                 listUser·p1.00:   8.421 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10139
  mean =      3.147 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 34 
    [2.000, 2.500) = 226 
    [2.500, 3.000) = 5705 
    [3.000, 3.500) = 1918 
    [3.500, 4.000) = 1007 
    [4.000, 4.500) = 870 
    [4.500, 5.000) = 242 
    [5.000, 5.500) = 51 
    [5.500, 6.000) = 22 
    [6.000, 6.500) = 23 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 11 
    [7.500, 8.000) = 9 
    [8.000, 8.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.153 ms/op
     p(99.9000) =      7.906 ms/op
     p(99.9900) =      8.417 ms/op
     p(99.9990) =      8.421 ms/op
     p(99.9999) =      8.421 ms/op
    p(100.0000) =      8.421 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.374          ops/ms
ClientSimple.existUser                       thrpt         12.455          ops/ms
ClientSimple.getUser                         thrpt         10.436          ops/ms
ClientSimple.listUser                        thrpt          8.389          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.668           ms/op
ClientSimple.createUser                     sample  14537   2.200 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.806           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.460           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.895           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.854           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.914           ms/op
ClientSimple.existUser                      sample  18141   1.763 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.285           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.608           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.587           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.988           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.768           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.821           ms/op
ClientSimple.getUser                        sample  16811   1.905 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.850           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.714           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.948           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.340           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.039           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample  10139   3.147 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.241           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.153           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.906           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.417           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.421           ms/op

Benchmark result is saved to 1722645724630.json
