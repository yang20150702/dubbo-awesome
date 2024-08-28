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
# Warmup Iteration   1: 1.532 ops/ms
Iteration   1: 6.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.360 ops/ms


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
# Warmup Iteration   1: 5.876 ops/ms
Iteration   1: 13.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.678 ops/ms


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
# Warmup Iteration   1: 6.053 ops/ms
Iteration   1: 12.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.249 ops/ms


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
# Warmup Iteration   1: 4.124 ops/ms
Iteration   1: 8.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.932 ops/ms


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.063 ms/op
Iteration   1: 2.303 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.303 ms/op


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
# Warmup Iteration   1: 3.322 ±(99.9%) 0.049 ms/op
Iteration   1: 1.898 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.898 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.056 ms/op
Iteration   1: 2.206 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.206 ms/op


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.082 ms/op
Iteration   1: 3.246 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.246 ms/op


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.095 ms/op
Iteration   1: 2.345 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  19.411 ms/op
                 createUser·p0.9999: 20.289 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13628
  mean =      2.345 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10238 
    [ 2.500,  5.000) = 3174 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     19.411 ms/op
     p(99.9900) =     20.289 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.065 ms/op
Iteration   1: 1.747 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   1.626 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  11.913 ms/op
                 existUser·p0.9999: 12.130 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18301
  mean =      1.747 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 825 
    [ 1.250,  2.500) = 16794 
    [ 2.500,  3.750) = 546 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      1.626 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     11.913 ms/op
     p(99.9900) =     12.130 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.091 ms/op
Iteration   1: 2.534 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.414 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 20.564 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12632
  mean =      2.534 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6440 
    [ 2.500,  5.000) = 6090 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     20.564 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.119 ms/op
Iteration   1: 3.863 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   9.330 ms/op
                 listUser·p0.999:  16.522 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8277
  mean =      3.863 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 380 
    [ 2.500,  5.000) = 7339 
    [ 5.000,  7.500) = 414 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      9.330 ms/op
     p(99.9000) =     16.522 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.360          ops/ms
ClientSimple.existUser                       thrpt         13.678          ops/ms
ClientSimple.getUser                         thrpt         12.249          ops/ms
ClientSimple.listUser                        thrpt          8.932          ops/ms
ClientSimple.createUser                       avgt          2.303           ms/op
ClientSimple.existUser                        avgt          1.898           ms/op
ClientSimple.getUser                          avgt          2.206           ms/op
ClientSimple.listUser                         avgt          3.246           ms/op
ClientSimple.createUser                     sample  13628   2.345 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.899           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.193           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.411           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.289           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.349           ms/op
ClientSimple.existUser                      sample  18301   1.747 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.746           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.626           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.088           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.913           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.130           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.239           ms/op
ClientSimple.getUser                        sample  12632   2.534 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.414           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.584           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.842           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.325           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.562           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.564           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.677           ms/op
ClientSimple.listUser                       sample   8277   3.863 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.904           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.330           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.522           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.513           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.513           ms/op

Benchmark result is saved to 1724825666692.json
