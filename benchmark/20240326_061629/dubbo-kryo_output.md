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
# Warmup Iteration   1: 1.762 ops/ms
Iteration   1: 7.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.365 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.524 ops/ms
Iteration   1: 11.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.823 ops/ms


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
# Warmup Iteration   1: 6.032 ops/ms
Iteration   1: 12.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.987 ops/ms


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
# Warmup Iteration   1: 6.658 ops/ms
Iteration   1: 9.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.207 ops/ms


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.090 ms/op
Iteration   1: 2.221 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.221 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.060 ms/op
Iteration   1: 1.852 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.054 ms/op
Iteration   1: 2.117 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.117 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.065 ±(99.9%) 0.114 ms/op
Iteration   1: 3.409 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.409 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.096 ms/op
Iteration   1: 2.215 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.007 ms/op
                 createUser·p0.99:   5.135 ms/op
                 createUser·p0.999:  19.900 ms/op
                 createUser·p0.9999: 20.333 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14714
  mean =      2.215 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11863 
    [ 2.500,  5.000) = 2686 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.007 ms/op
     p(99.0000) =      5.135 ms/op
     p(99.9000) =     19.900 ms/op
     p(99.9900) =     20.333 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 3.025 ±(99.9%) 0.076 ms/op
Iteration   1: 2.268 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   2.154 ms/op
                 existUser·p0.90:   2.707 ms/op
                 existUser·p0.95:   2.872 ms/op
                 existUser·p0.99:   4.965 ms/op
                 existUser·p0.999:  24.602 ms/op
                 existUser·p0.9999: 25.728 ms/op
                 existUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14195
  mean =      2.268 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10917 
    [ 2.500,  5.000) = 3139 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.872 ms/op
     p(99.0000) =      4.965 ms/op
     p(99.9000) =     24.602 ms/op
     p(99.9900) =     25.728 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 3.499 ±(99.9%) 0.094 ms/op
Iteration   1: 2.064 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   1.851 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   5.108 ms/op
                 getUser·p0.999:  13.351 ms/op
                 getUser·p0.9999: 14.702 ms/op
                 getUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15548
  mean =      2.064 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 13086 
    [ 2.500,  3.750) = 2043 
    [ 3.750,  5.000) = 181 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      5.108 ms/op
     p(99.9000) =     13.351 ms/op
     p(99.9900) =     14.702 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.131 ms/op
Iteration   1: 3.468 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.643 ms/op
                 listUser·p0.999:  12.108 ms/op
                 listUser·p0.9999: 12.173 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9248
  mean =      3.468 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 587 
    [ 2.500,  3.750) = 6424 
    [ 3.750,  5.000) = 1759 
    [ 5.000,  6.250) = 214 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      8.643 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.365          ops/ms
ClientSimple.existUser                       thrpt         11.823          ops/ms
ClientSimple.getUser                         thrpt         12.987          ops/ms
ClientSimple.listUser                        thrpt          9.207          ops/ms
ClientSimple.createUser                       avgt          2.221           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          2.117           ms/op
ClientSimple.listUser                         avgt          3.409           ms/op
ClientSimple.createUser                     sample  14714   2.215 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.577           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.007           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.135           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.900           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.333           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.349           ms/op
ClientSimple.existUser                      sample  14195   2.268 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.872           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.965           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.602           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.728           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.756           ms/op
ClientSimple.getUser                        sample  15548   2.064 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.738           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.851           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.108           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.351           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.702           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.811           ms/op
ClientSimple.listUser                       sample   9248   3.468 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.290           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.643           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.108           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.173           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.173           ms/op

Benchmark result is saved to 1711433521833.json
