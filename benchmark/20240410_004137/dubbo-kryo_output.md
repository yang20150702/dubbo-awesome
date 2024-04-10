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
# Warmup Iteration   1: 1.423 ops/ms
Iteration   1: 6.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.686 ops/ms


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
# Warmup Iteration   1: 6.458 ops/ms
Iteration   1: 14.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.121 ops/ms


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
# Warmup Iteration   1: 6.486 ops/ms
Iteration   1: 13.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.700 ops/ms


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
# Warmup Iteration   1: 5.296 ops/ms
Iteration   1: 8.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.569 ops/ms


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.104 ms/op
Iteration   1: 2.161 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.161 ms/op


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
# Warmup Iteration   1: 2.923 ±(99.9%) 0.043 ms/op
Iteration   1: 1.916 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.061 ms/op
Iteration   1: 2.382 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.382 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.089 ms/op
Iteration   1: 3.326 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.326 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.096 ms/op
Iteration   1: 2.111 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.536 ms/op
                 createUser·p0.95:   2.773 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  16.400 ms/op
                 createUser·p0.9999: 16.990 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15117
  mean =      2.111 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 13346 
    [ 2.500,  3.750) = 1593 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.536 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     16.990 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.088 ms/op
Iteration   1: 1.784 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.038 ms/op
                 existUser·p0.95:   2.281 ms/op
                 existUser·p0.99:   2.765 ms/op
                 existUser·p0.999:  10.465 ms/op
                 existUser·p0.9999: 11.354 ms/op
                 existUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18238
  mean =      1.784 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 17770 
    [ 2.500,  3.750) = 327 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.038 ms/op
     p(95.0000) =      2.281 ms/op
     p(99.0000) =      2.765 ms/op
     p(99.9000) =     10.465 ms/op
     p(99.9900) =     11.354 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.078 ms/op
Iteration   1: 1.868 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.472 ms/op
                 getUser·p0.50:   1.731 ms/op
                 getUser·p0.90:   2.228 ms/op
                 getUser·p0.95:   2.421 ms/op
                 getUser·p0.99:   3.556 ms/op
                 getUser·p0.999:  16.905 ms/op
                 getUser·p0.9999: 17.363 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17096
  mean =      1.868 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 650 
    [ 1.250,  2.500) = 15748 
    [ 2.500,  3.750) = 536 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      3.556 ms/op
     p(99.9000) =     16.905 ms/op
     p(99.9900) =     17.363 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.121 ms/op
Iteration   1: 3.421 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.246 ms/op
                 listUser·p0.999:  5.951 ms/op
                 listUser·p0.9999: 8.913 ms/op
                 listUser·p1.00:   8.913 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9388
  mean =      3.421 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 86 
    [2.000, 2.500) = 758 
    [2.500, 3.000) = 2189 
    [3.000, 3.500) = 1659 
    [3.500, 4.000) = 2754 
    [4.000, 4.500) = 1564 
    [4.500, 5.000) = 236 
    [5.000, 5.500) = 78 
    [5.500, 6.000) = 54 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.246 ms/op
     p(99.9000) =      5.951 ms/op
     p(99.9900) =      8.913 ms/op
     p(99.9990) =      8.913 ms/op
     p(99.9999) =      8.913 ms/op
    p(100.0000) =      8.913 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.686          ops/ms
ClientSimple.existUser                       thrpt         14.121          ops/ms
ClientSimple.getUser                         thrpt         13.700          ops/ms
ClientSimple.listUser                        thrpt          8.569          ops/ms
ClientSimple.createUser                       avgt          2.161           ms/op
ClientSimple.existUser                        avgt          1.916           ms/op
ClientSimple.getUser                          avgt          2.382           ms/op
ClientSimple.listUser                         avgt          3.326           ms/op
ClientSimple.createUser                     sample  15117   2.111 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.816           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.536           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.309           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.400           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.990           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.007           ms/op
ClientSimple.existUser                      sample  18238   1.784 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.805           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.038           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.465           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.354           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.354           ms/op
ClientSimple.getUser                        sample  17096   1.868 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.472           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.731           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.228           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.556           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.905           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.363           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.433           ms/op
ClientSimple.listUser                       sample   9388   3.421 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.329           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.246           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.951           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.913           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.913           ms/op

Benchmark result is saved to 1712709435442.json
