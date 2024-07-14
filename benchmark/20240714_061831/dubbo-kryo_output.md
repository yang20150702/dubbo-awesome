# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.619 ops/ms
Iteration   1: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.490 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.460 ops/ms
Iteration   1: 11.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.893 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ops/ms
Iteration   1: 13.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.015 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.432 ops/ms
Iteration   1: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.697 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.070 ms/op
Iteration   1: 2.183 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ±(99.9%) 0.047 ms/op
Iteration   1: 2.121 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ±(99.9%) 0.057 ms/op
Iteration   1: 2.056 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.056 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.254 ±(99.9%) 0.079 ms/op
Iteration   1: 3.531 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.085 ms/op
Iteration   1: 1.986 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   1.733 ms/op
                 createUser·p0.90:   2.425 ms/op
                 createUser·p0.95:   2.746 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  17.627 ms/op
                 createUser·p0.9999: 17.786 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16073
  mean =      1.986 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 14514 
    [ 2.500,  3.750) = 919 
    [ 3.750,  5.000) = 188 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.746 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     17.627 ms/op
     p(99.9900) =     17.786 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.947 ±(99.9%) 0.068 ms/op
Iteration   1: 2.008 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.072 ms/op
                 existUser·p0.999:  12.893 ms/op
                 existUser·p0.9999: 15.685 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16069
  mean =      2.008 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 310 
    [ 1.250,  2.500) = 13544 
    [ 2.500,  3.750) = 2163 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.072 ms/op
     p(99.9000) =     12.893 ms/op
     p(99.9900) =     15.685 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.182 ±(99.9%) 0.078 ms/op
Iteration   1: 2.069 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.005 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.998 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 12.581 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15458
  mean =      2.069 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 271 
    [ 1.250,  2.500) = 12258 
    [ 2.500,  3.750) = 2839 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.581 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.117 ms/op
Iteration   1: 3.105 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.555 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 17.886 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10296
  mean =      3.105 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 375 
    [ 2.500,  3.750) = 8803 
    [ 3.750,  5.000) = 965 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     17.886 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.490          ops/ms
ClientSimple.existUser                       thrpt         11.893          ops/ms
ClientSimple.getUser                         thrpt         13.015          ops/ms
ClientSimple.listUser                        thrpt          8.697          ops/ms
ClientSimple.createUser                       avgt          2.183           ms/op
ClientSimple.existUser                        avgt          2.121           ms/op
ClientSimple.getUser                          avgt          2.056           ms/op
ClientSimple.listUser                         avgt          3.531           ms/op
ClientSimple.createUser                     sample  16073   1.986 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.792           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.733           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.425           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.746           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.250           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.627           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.786           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.826           ms/op
ClientSimple.existUser                      sample  16069   2.008 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.072           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.893           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.685           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.745           ms/op
ClientSimple.getUser                        sample  15458   2.069 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.714           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.005           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.998           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.531           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.581           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.599           ms/op
ClientSimple.listUser                       sample  10296   3.105 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.555           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.785           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.382           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.564           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.886           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.891           ms/op

Benchmark result is saved to 1720937653631.json
