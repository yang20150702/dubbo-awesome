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
# Warmup Iteration   1: 1.910 ops/ms
Iteration   1: 6.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.830 ops/ms


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
# Warmup Iteration   1: 6.212 ops/ms
Iteration   1: 11.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.881 ops/ms


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
# Warmup Iteration   1: 5.225 ops/ms
Iteration   1: 14.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.069 ops/ms


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
# Warmup Iteration   1: 6.109 ops/ms
Iteration   1: 8.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.609 ops/ms


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.067 ms/op
Iteration   1: 2.130 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.130 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.051 ms/op
Iteration   1: 1.950 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.950 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.057 ms/op
Iteration   1: 1.887 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.887 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.117 ms/op
Iteration   1: 3.529 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.529 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.088 ms/op
Iteration   1: 2.257 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  30.704 ms/op
                 createUser·p0.9999: 32.375 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14163
  mean =      2.257 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11590 
    [ 2.500,  5.000) = 2329 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 3.025 ±(99.9%) 0.090 ms/op
Iteration   1: 1.794 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   1.657 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   4.265 ms/op
                 existUser·p0.999:  12.602 ms/op
                 existUser·p0.9999: 13.247 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17912
  mean =      1.794 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 329 
    [ 1.250,  2.500) = 16945 
    [ 2.500,  3.750) = 447 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.657 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      4.265 ms/op
     p(99.9000) =     12.602 ms/op
     p(99.9900) =     13.247 ms/op
     p(99.9990) =     13.402 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.085 ms/op
Iteration   1: 2.027 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   1.851 ms/op
                 getUser·p0.90:   2.523 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   3.457 ms/op
                 getUser·p0.999:  17.236 ms/op
                 getUser·p0.9999: 17.605 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15768
  mean =      2.027 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 14002 
    [ 2.500,  3.750) = 1539 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.605 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.109 ms/op
Iteration   1: 2.949 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   2.753 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.018 ms/op
                 listUser·p0.99:   4.792 ms/op
                 listUser·p0.999:  6.275 ms/op
                 listUser·p0.9999: 7.490 ms/op
                 listUser·p1.00:   7.586 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10853
  mean =      2.949 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 11 
    [1.500, 2.000) = 99 
    [2.000, 2.500) = 2110 
    [2.500, 3.000) = 4757 
    [3.000, 3.500) = 1761 
    [3.500, 4.000) = 1530 
    [4.000, 4.500) = 403 
    [4.500, 5.000) = 114 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 22 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      6.275 ms/op
     p(99.9900) =      7.490 ms/op
     p(99.9990) =      7.586 ms/op
     p(99.9999) =      7.586 ms/op
    p(100.0000) =      7.586 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.830          ops/ms
ClientSimple.existUser                       thrpt         11.881          ops/ms
ClientSimple.getUser                         thrpt         14.069          ops/ms
ClientSimple.listUser                        thrpt          8.609          ops/ms
ClientSimple.createUser                       avgt          2.130           ms/op
ClientSimple.existUser                        avgt          1.950           ms/op
ClientSimple.getUser                          avgt          1.887           ms/op
ClientSimple.listUser                         avgt          3.529           ms/op
ClientSimple.createUser                     sample  14163   2.257 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.631           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.029           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.704           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.375           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.375           ms/op
ClientSimple.existUser                      sample  17912   1.794 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.541           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.657           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.265           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.602           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.247           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.402           ms/op
ClientSimple.getUser                        sample  15768   2.027 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.851           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.457           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.236           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.605           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.662           ms/op
ClientSimple.listUser                       sample  10853   2.949 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.011           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.753           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.760           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.018           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.275           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.490           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.586           ms/op

Benchmark result is saved to 1712599911454.json
