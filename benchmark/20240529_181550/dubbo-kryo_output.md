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
# Warmup Iteration   1: 1.498 ops/ms
Iteration   1: 6.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.178 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.724 ops/ms
Iteration   1: 10.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.987 ops/ms


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
# Warmup Iteration   1: 5.192 ops/ms
Iteration   1: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.426 ops/ms


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
# Warmup Iteration   1: 4.863 ops/ms
Iteration   1: 8.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.511 ops/ms


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.068 ms/op
Iteration   1: 2.286 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.286 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.068 ms/op
Iteration   1: 1.746 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.746 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.074 ms/op
Iteration   1: 2.358 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.358 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.516 ±(99.9%) 0.095 ms/op
Iteration   1: 3.193 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.193 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ±(99.9%) 0.100 ms/op
Iteration   1: 2.386 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.245 ms/op
                 createUser·p0.90:   2.781 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   10.148 ms/op
                 createUser·p0.999:  23.364 ms/op
                 createUser·p0.9999: 25.482 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13402
  mean =      2.386 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10126 
    [ 2.500,  5.000) = 3030 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      2.245 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =     10.148 ms/op
     p(99.9000) =     23.364 ms/op
     p(99.9900) =     25.482 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.073 ms/op
Iteration   1: 2.056 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.317 ms/op
                 existUser·p0.50:   1.960 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  19.726 ms/op
                 existUser·p0.9999: 20.032 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15546
  mean =      2.056 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13536 
    [ 2.500,  5.000) = 1969 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.317 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.420 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     20.032 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.103 ms/op
Iteration   1: 2.119 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.802 ms/op
                 getUser·p0.95:   3.015 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  12.826 ms/op
                 getUser·p0.9999: 13.156 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15179
  mean =      2.119 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 314 
    [ 1.250,  2.500) = 11368 
    [ 2.500,  3.750) = 3300 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =     12.826 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.137 ms/op
Iteration   1: 3.572 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.138 ms/op
                 listUser·p0.999:  22.644 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8960
  mean =      3.572 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 534 
    [ 2.500,  5.000) = 8115 
    [ 5.000,  7.500) = 247 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.138 ms/op
     p(99.9000) =     22.644 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.178          ops/ms
ClientSimple.existUser                       thrpt         10.987          ops/ms
ClientSimple.getUser                         thrpt         10.426          ops/ms
ClientSimple.listUser                        thrpt          8.511          ops/ms
ClientSimple.createUser                       avgt          2.286           ms/op
ClientSimple.existUser                        avgt          1.746           ms/op
ClientSimple.getUser                          avgt          2.358           ms/op
ClientSimple.listUser                         avgt          3.193           ms/op
ClientSimple.createUser                     sample  13402   2.386 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.041           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.245           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.148           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.364           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.482           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.494           ms/op
ClientSimple.existUser                      sample  15546   2.056 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.317           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.960           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.420           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.726           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.032           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.087           ms/op
ClientSimple.getUser                        sample  15179   2.119 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.752           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.015           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.268           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.826           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.156           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.156           ms/op
ClientSimple.listUser                       sample   8960   3.572 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.276           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.514           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.138           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.644           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.774           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.774           ms/op

Benchmark result is saved to 1717006297130.json
