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
# Warmup Iteration   1: 1.543 ops/ms
Iteration   1: 5.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.926 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ops/ms
Iteration   1: 12.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.360 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ops/ms
Iteration   1: 10.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.344 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.980 ops/ms
Iteration   1: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.755 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.089 ms/op
Iteration   1: 2.158 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.158 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.474 ±(99.9%) 0.068 ms/op
Iteration   1: 2.017 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.017 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ±(99.9%) 0.060 ms/op
Iteration   1: 2.158 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.158 ms/op


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.082 ms/op
Iteration   1: 3.879 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.879 ms/op


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.102 ms/op
Iteration   1: 2.142 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   10.582 ms/op
                 createUser·p0.999:  21.236 ms/op
                 createUser·p0.9999: 21.480 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14962
  mean =      2.142 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12063 
    [ 2.500,  5.000) = 2595 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =     10.582 ms/op
     p(99.9000) =     21.236 ms/op
     p(99.9900) =     21.480 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.089 ms/op
Iteration   1: 2.022 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.307 ms/op
                 existUser·p0.999:  21.677 ms/op
                 existUser·p0.9999: 23.097 ms/op
                 existUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15820
  mean =      2.022 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14325 
    [ 2.500,  5.000) = 1366 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.307 ms/op
     p(99.9000) =     21.677 ms/op
     p(99.9900) =     23.097 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.127 ms/op
Iteration   1: 2.034 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  13.386 ms/op
                 getUser·p0.9999: 14.067 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15739
  mean =      2.034 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 13941 
    [ 2.500,  3.750) = 1473 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     14.067 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.183 ms/op
Iteration   1: 3.626 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.628 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8811
  mean =      3.626 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 728 
    [ 2.500,  5.000) = 7688 
    [ 5.000,  7.500) = 305 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.628 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.926          ops/ms
ClientSimple.existUser                       thrpt         12.360          ops/ms
ClientSimple.getUser                         thrpt         10.344          ops/ms
ClientSimple.listUser                        thrpt          8.755          ops/ms
ClientSimple.createUser                       avgt          2.158           ms/op
ClientSimple.existUser                        avgt          2.017           ms/op
ClientSimple.getUser                          avgt          2.158           ms/op
ClientSimple.listUser                         avgt          3.879           ms/op
ClientSimple.createUser                     sample  14962   2.142 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.601           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.582           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.480           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.496           ms/op
ClientSimple.existUser                      sample  15820   2.022 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.680           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.307           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.677           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.097           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.593           ms/op
ClientSimple.getUser                        sample  15739   2.034 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.532           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.846           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.386           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.067           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.123           ms/op
ClientSimple.listUser                       sample   8811   3.626 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.888           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.956           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.628           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.055           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.840           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.840           ms/op

Benchmark result is saved to 1711109693563.json
