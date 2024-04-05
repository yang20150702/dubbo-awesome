# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.685 ops/ms
Iteration   1: 6.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.684 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.546 ops/ms
Iteration   1: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.896 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.537 ops/ms
Iteration   1: 13.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.799 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ops/ms
Iteration   1: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.401 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.017 ±(99.9%) 0.078 ms/op
Iteration   1: 2.354 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.354 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ±(99.9%) 0.052 ms/op
Iteration   1: 1.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.961 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ±(99.9%) 0.065 ms/op
Iteration   1: 1.816 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.816 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ±(99.9%) 0.088 ms/op
Iteration   1: 3.039 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.039 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.234 ±(99.9%) 0.080 ms/op
Iteration   1: 2.370 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   3.404 ms/op
                 createUser·p0.99:   8.671 ms/op
                 createUser·p0.999:  32.167 ms/op
                 createUser·p0.9999: 32.570 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13488
  mean =      2.370 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10995 
    [ 2.500,  5.000) = 2174 
    [ 5.000,  7.500) = 158 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.404 ms/op
     p(99.0000) =      8.671 ms/op
     p(99.9000) =     32.167 ms/op
     p(99.9900) =     32.570 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ±(99.9%) 0.067 ms/op
Iteration   1: 1.833 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.286 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.510 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  18.022 ms/op
                 existUser·p0.9999: 18.703 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17443
  mean =      1.833 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 657 
    [ 1.250,  2.500) = 15896 
    [ 2.500,  3.750) = 715 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.510 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     18.703 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.175 ±(99.9%) 0.092 ms/op
Iteration   1: 1.888 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   1.780 ms/op
                 getUser·p0.90:   2.191 ms/op
                 getUser·p0.95:   2.392 ms/op
                 getUser·p0.99:   3.025 ms/op
                 getUser·p0.999:  16.007 ms/op
                 getUser·p0.9999: 16.094 ms/op
                 getUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16957
  mean =      1.888 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 16252 
    [ 2.500,  3.750) = 471 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.025 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     16.094 ms/op
     p(99.9990) =     16.105 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.487 ±(99.9%) 0.148 ms/op
Iteration   1: 3.216 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.396 ms/op
                 listUser·p0.99:   5.684 ms/op
                 listUser·p0.999:  7.561 ms/op
                 listUser·p0.9999: 7.733 ms/op
                 listUser·p1.00:   7.733 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10007
  mean =      3.216 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 46 
    [2.000, 2.500) = 331 
    [2.500, 3.000) = 5145 
    [3.000, 3.500) = 1767 
    [3.500, 4.000) = 1244 
    [4.000, 4.500) = 1046 
    [4.500, 5.000) = 183 
    [5.000, 5.500) = 116 
    [5.500, 6.000) = 66 
    [6.000, 6.500) = 37 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.396 ms/op
     p(99.0000) =      5.684 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =      7.733 ms/op
     p(99.9990) =      7.733 ms/op
     p(99.9999) =      7.733 ms/op
    p(100.0000) =      7.733 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.684          ops/ms
ClientSimple.existUser                       thrpt         12.896          ops/ms
ClientSimple.getUser                         thrpt         13.799          ops/ms
ClientSimple.listUser                        thrpt          8.401          ops/ms
ClientSimple.createUser                       avgt          2.354           ms/op
ClientSimple.existUser                        avgt          1.961           ms/op
ClientSimple.getUser                          avgt          1.816           ms/op
ClientSimple.listUser                         avgt          3.039           ms/op
ClientSimple.createUser                     sample  13488   2.370 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.439           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.404           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.671           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.167           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.570           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.604           ms/op
ClientSimple.existUser                      sample  17443   1.833 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.286           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.714           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.510           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.752           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.022           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.703           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.776           ms/op
ClientSimple.getUser                        sample  16957   1.888 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.698           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.780           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.025           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.007           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.094           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.105           ms/op
ClientSimple.listUser                       sample  10007   3.216 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.396           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.684           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.561           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.733           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.733           ms/op

Benchmark result is saved to 1712297478152.json
