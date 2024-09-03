# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.955 ops/ms
Iteration   1: 6.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.832 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.149 ops/ms
Iteration   1: 13.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.855 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.048 ops/ms
Iteration   1: 13.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.565 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
Iteration   1: 8.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.078 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.068 ms/op
Iteration   1: 2.242 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.242 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.548 ±(99.9%) 0.062 ms/op
Iteration   1: 1.678 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.678 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.060 ms/op
Iteration   1: 2.484 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.484 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.662 ±(99.9%) 0.160 ms/op
Iteration   1: 3.366 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.366 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ±(99.9%) 0.100 ms/op
Iteration   1: 2.182 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   2.019 ms/op
                 createUser·p0.90:   2.507 ms/op
                 createUser·p0.95:   2.806 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  20.105 ms/op
                 createUser·p0.9999: 22.614 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14718
  mean =      2.182 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13204 
    [ 2.500,  5.000) = 1285 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     20.105 ms/op
     p(99.9900) =     22.614 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.878 ±(99.9%) 0.062 ms/op
Iteration   1: 2.060 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.038 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.753 ms/op
                 existUser·p0.99:   3.239 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 10.981 ms/op
                 existUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15525
  mean =      2.060 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 12996 
    [ 2.500,  3.750) = 2206 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.239 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     10.981 ms/op
     p(99.9990) =     11.026 ms/op
     p(99.9999) =     11.026 ms/op
    p(100.0000) =     11.026 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.112 ms/op
Iteration   1: 2.279 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.251 ms/op
                 getUser·p0.50:   2.232 ms/op
                 getUser·p0.90:   2.892 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  16.769 ms/op
                 getUser·p0.9999: 17.667 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14237
  mean =      2.279 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 9483 
    [ 2.500,  3.750) = 4461 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.251 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =     16.769 ms/op
     p(99.9900) =     17.667 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.455 ±(99.9%) 0.124 ms/op
Iteration   1: 3.469 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  21.277 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9220
  mean =      3.469 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 998 
    [ 2.500,  5.000) = 7926 
    [ 5.000,  7.500) = 200 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     21.277 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.832          ops/ms
ClientSimple.existUser                       thrpt         13.855          ops/ms
ClientSimple.getUser                         thrpt         13.565          ops/ms
ClientSimple.listUser                        thrpt          8.078          ops/ms
ClientSimple.createUser                       avgt          2.242           ms/op
ClientSimple.existUser                        avgt          1.678           ms/op
ClientSimple.getUser                          avgt          2.484           ms/op
ClientSimple.listUser                         avgt          3.366           ms/op
ClientSimple.createUser                     sample  14718   2.182 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.537           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.019           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.733           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.105           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.614           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.675           ms/op
ClientSimple.existUser                      sample  15525   2.060 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.658           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.038           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.239           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.699           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.981           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.026           ms/op
ClientSimple.getUser                        sample  14237   2.279 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.251           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.232           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.125           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.018           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.769           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.667           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.695           ms/op
ClientSimple.listUser                       sample   9220   3.469 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.313           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.586           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.277           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.332           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.332           ms/op

Benchmark result is saved to 1725324294788.json
