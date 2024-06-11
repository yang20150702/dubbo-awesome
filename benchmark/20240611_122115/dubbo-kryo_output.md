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
# Warmup Iteration   1: 2.220 ops/ms
Iteration   1: 8.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.842 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.903 ops/ms
Iteration   1: 14.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.527 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.828 ops/ms
Iteration   1: 14.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.407 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.661 ops/ms
Iteration   1: 10.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.171 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.085 ms/op
Iteration   1: 2.190 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.190 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.055 ms/op
Iteration   1: 1.833 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 2.916 ±(99.9%) 0.050 ms/op
Iteration   1: 2.049 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.049 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.118 ms/op
Iteration   1: 3.113 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.113 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.076 ms/op
Iteration   1: 2.145 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.420 ms/op
                 createUser·p0.50:   1.931 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.634 ms/op
                 createUser·p0.99:   4.869 ms/op
                 createUser·p0.999:  33.489 ms/op
                 createUser·p0.9999: 33.883 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14932
  mean =      2.145 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13710 
    [ 2.500,  5.000) = 1075 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      4.869 ms/op
     p(99.9000) =     33.489 ms/op
     p(99.9900) =     33.883 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.964 ±(99.9%) 0.068 ms/op
Iteration   1: 1.920 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.311 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  11.595 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16635
  mean =      1.920 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 457 
    [ 1.250,  2.500) = 15000 
    [ 2.500,  3.750) = 1033 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.311 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =     11.595 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ±(99.9%) 0.078 ms/op
Iteration   1: 1.919 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   1.847 ms/op
                 getUser·p0.90:   2.294 ms/op
                 getUser·p0.95:   2.413 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  13.401 ms/op
                 getUser·p0.9999: 14.367 ms/op
                 getUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17088
  mean =      1.919 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 324 
    [ 1.250,  2.500) = 16144 
    [ 2.500,  3.750) = 400 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =     13.401 ms/op
     p(99.9900) =     14.367 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ±(99.9%) 0.128 ms/op
Iteration   1: 3.097 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.645 ms/op
                 listUser·p0.95:   3.932 ms/op
                 listUser·p0.99:   5.634 ms/op
                 listUser·p0.999:  25.461 ms/op
                 listUser·p0.9999: 25.558 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10324
  mean =      3.097 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 310 
    [ 2.500,  5.000) = 9847 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.634 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     25.558 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.842          ops/ms
ClientSimple.existUser                       thrpt         14.527          ops/ms
ClientSimple.getUser                         thrpt         14.407          ops/ms
ClientSimple.listUser                        thrpt         10.171          ops/ms
ClientSimple.createUser                       avgt          2.190           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          2.049           ms/op
ClientSimple.listUser                         avgt          3.113           ms/op
ClientSimple.createUser                     sample  14932   2.145 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.420           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.931           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.869           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.489           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.883           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.948           ms/op
ClientSimple.existUser                      sample  16635   1.920 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.311           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.432           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.595           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.239           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.239           ms/op
ClientSimple.getUser                        sample  17088   1.919 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.558           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.847           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.294           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.219           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.401           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.367           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.402           ms/op
ClientSimple.listUser                       sample  10324   3.097 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.821           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.634           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.461           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.558           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.559           ms/op

Benchmark result is saved to 1718108232544.json
