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
# Warmup Iteration   1: 1.960 ops/ms
Iteration   1: 8.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.541 ops/ms


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
# Warmup Iteration   1: 6.523 ops/ms
Iteration   1: 12.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.421 ops/ms


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
# Warmup Iteration   1: 6.689 ops/ms
Iteration   1: 13.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.495 ops/ms


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
# Warmup Iteration   1: 5.697 ops/ms
Iteration   1: 8.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.847 ops/ms


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.066 ms/op
Iteration   1: 2.146 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.146 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.048 ms/op
Iteration   1: 1.981 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.981 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.065 ms/op
Iteration   1: 2.024 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.024 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.088 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.312 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.163 ms/op
Iteration   1: 2.292 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  18.091 ms/op
                 createUser·p0.9999: 21.208 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13951
  mean =      2.292 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11094 
    [ 2.500,  5.000) = 2606 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     18.091 ms/op
     p(99.9900) =     21.208 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.076 ms/op
Iteration   1: 2.022 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   0.327 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  76.284 ms/op
                 existUser·p0.9999: 77.515 ms/op
                 existUser·p1.00:   78.512 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15850
  mean =      2.022 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15630 
    [ 5.000, 10.000) = 124 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     76.284 ms/op
     p(99.9900) =     77.515 ms/op
     p(99.9990) =     78.512 ms/op
     p(99.9999) =     78.512 ms/op
    p(100.0000) =     78.512 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.085 ms/op
Iteration   1: 1.973 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.422 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  18.483 ms/op
                 getUser·p0.9999: 21.545 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16459
  mean =      1.973 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14884 
    [ 2.500,  5.000) = 1487 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =     18.483 ms/op
     p(99.9900) =     21.545 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.120 ms/op
Iteration   1: 3.402 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.852 ms/op
                 listUser·p0.999:  11.641 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9489
  mean =      3.402 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 453 
    [ 2.500,  3.750) = 6478 
    [ 3.750,  5.000) = 2350 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.852 ms/op
     p(99.9000) =     11.641 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.541          ops/ms
ClientSimple.existUser                       thrpt         12.421          ops/ms
ClientSimple.getUser                         thrpt         13.495          ops/ms
ClientSimple.listUser                        thrpt          8.847          ops/ms
ClientSimple.createUser                       avgt          2.146           ms/op
ClientSimple.existUser                        avgt          1.981           ms/op
ClientSimple.getUser                          avgt          2.024           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  13951   2.292 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.596           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.938           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.091           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.208           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.234           ms/op
ClientSimple.existUser                      sample  15850   2.022 ± 0.095   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.327           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.554           ms/op
ClientSimple.existUser:existUser·p0.999     sample         76.284           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         77.515           ms/op
ClientSimple.existUser:existUser·p1.00      sample         78.512           ms/op
ClientSimple.getUser                        sample  16459   1.973 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.422           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.695           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.483           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.545           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.053           ms/op
ClientSimple.listUser                       sample   9489   3.402 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.425           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.852           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.641           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.239           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.239           ms/op

Benchmark result is saved to 1715623802772.json
