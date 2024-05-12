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
# Warmup Iteration   1: 1.437 ops/ms
Iteration   1: 7.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.101 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.779 ops/ms
Iteration   1: 13.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.588 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ops/ms
Iteration   1: 11.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.882 ops/ms


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
# Warmup Iteration   1: 4.012 ops/ms
Iteration   1: 8.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.814 ops/ms


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.082 ms/op
Iteration   1: 2.273 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.273 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.065 ms/op
Iteration   1: 2.237 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.237 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.062 ms/op
Iteration   1: 2.101 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.101 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.091 ms/op
Iteration   1: 3.219 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.219 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.118 ms/op
Iteration   1: 2.157 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.140 ms/op
                 createUser·p0.99:   4.783 ms/op
                 createUser·p0.999:  22.020 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14808
  mean =      2.157 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11874 
    [ 2.500,  5.000) = 2800 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.140 ms/op
     p(99.0000) =      4.783 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 2.914 ±(99.9%) 0.069 ms/op
Iteration   1: 1.801 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  17.012 ms/op
                 existUser·p0.9999: 17.661 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17841
  mean =      1.801 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 605 
    [ 1.250,  2.500) = 16202 
    [ 2.500,  3.750) = 862 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     17.012 ms/op
     p(99.9900) =     17.661 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.083 ms/op
Iteration   1: 2.232 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.931 ms/op
                 getUser·p0.99:   5.552 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 18.507 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14427
  mean =      2.232 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 291 
    [ 1.250,  2.500) = 11321 
    [ 2.500,  3.750) = 2516 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.931 ms/op
     p(99.0000) =      5.552 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     18.507 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.128 ms/op
Iteration   1: 3.665 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  21.037 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8743
  mean =      3.665 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 950 
    [ 2.500,  5.000) = 7458 
    [ 5.000,  7.500) = 271 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.101          ops/ms
ClientSimple.existUser                       thrpt         13.588          ops/ms
ClientSimple.getUser                         thrpt         11.882          ops/ms
ClientSimple.listUser                        thrpt          8.814          ops/ms
ClientSimple.createUser                       avgt          2.273           ms/op
ClientSimple.existUser                        avgt          2.237           ms/op
ClientSimple.getUser                          avgt          2.101           ms/op
ClientSimple.listUser                         avgt          3.219           ms/op
ClientSimple.createUser                     sample  14808   2.157 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.931           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.140           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.783           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.020           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.200           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.200           ms/op
ClientSimple.existUser                      sample  17841   1.801 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.526           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.666           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.012           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.661           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.252           ms/op
ClientSimple.getUser                        sample  14427   2.232 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.510           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.931           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.552           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.433           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.507           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.711           ms/op
ClientSimple.listUser                       sample   8743   3.665 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.153           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.332           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.037           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.725           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.725           ms/op

Benchmark result is saved to 1715474548653.json
