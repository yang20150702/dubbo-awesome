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
# Warmup Iteration   1: 1.860 ops/ms
Iteration   1: 7.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.164 ops/ms


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
# Warmup Iteration   1: 5.979 ops/ms
Iteration   1: 11.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.683 ops/ms


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
# Warmup Iteration   1: 5.486 ops/ms
Iteration   1: 12.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.191 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.152 ops/ms
Iteration   1: 8.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.746 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.220 ±(99.9%) 0.072 ms/op
Iteration   1: 2.037 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.037 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.047 ms/op
Iteration   1: 1.765 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.765 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.494 ±(99.9%) 0.060 ms/op
Iteration   1: 2.099 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.099 ms/op


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.085 ms/op
Iteration   1: 3.665 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.665 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.094 ms/op
Iteration   1: 2.274 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   5.050 ms/op
                 createUser·p0.999:  16.417 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14050
  mean =      2.274 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 11520 
    [ 2.500,  3.750) = 2094 
    [ 3.750,  5.000) = 174 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      5.050 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.069 ms/op
Iteration   1: 2.071 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 17.902 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15591
  mean =      2.071 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 311 
    [ 1.250,  2.500) = 13878 
    [ 2.500,  3.750) = 1241 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     17.902 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.087 ms/op
Iteration   1: 2.004 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   1.780 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  29.131 ms/op
                 getUser·p0.9999: 32.894 ms/op
                 getUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15947
  mean =      2.004 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13916 
    [ 2.500,  5.000) = 1897 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     32.894 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 4.921 ±(99.9%) 0.151 ms/op
Iteration   1: 3.068 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   5.284 ms/op
                 listUser·p0.999:  13.772 ms/op
                 listUser·p0.9999: 15.167 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10442
  mean =      3.068 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 698 
    [ 2.500,  3.750) = 8339 
    [ 3.750,  5.000) = 1258 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     13.772 ms/op
     p(99.9900) =     15.167 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.164          ops/ms
ClientSimple.existUser                       thrpt         11.683          ops/ms
ClientSimple.getUser                         thrpt         12.191          ops/ms
ClientSimple.listUser                        thrpt          8.746          ops/ms
ClientSimple.createUser                       avgt          2.037           ms/op
ClientSimple.existUser                        avgt          1.765           ms/op
ClientSimple.getUser                          avgt          2.099           ms/op
ClientSimple.listUser                         avgt          3.665           ms/op
ClientSimple.createUser                     sample  14050   2.274 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.001           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.050           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.417           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.317           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.317           ms/op
ClientSimple.existUser                      sample  15591   2.071 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.423           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.793           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.727           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.902           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.957           ms/op
ClientSimple.getUser                        sample  15947   2.004 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.558           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.780           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.096           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.131           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         32.894           ms/op
ClientSimple.getUser:getUser·p1.00          sample         37.552           ms/op
ClientSimple.listUser                       sample  10442   3.068 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.610           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.830           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.284           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.772           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.167           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.172           ms/op

Benchmark result is saved to 1712124663576.json
