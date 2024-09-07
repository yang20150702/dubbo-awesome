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
# Warmup Iteration   1: 1.398 ops/ms
Iteration   1: 6.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.034 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.003 ops/ms
Iteration   1: 11.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.955 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ops/ms
Iteration   1: 13.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.264 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ops/ms
Iteration   1: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.431 ops/ms


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.088 ms/op
Iteration   1: 2.310 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.310 ms/op


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.071 ms/op
Iteration   1: 2.196 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.196 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.061 ms/op
Iteration   1: 1.901 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.901 ms/op


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
# Warmup Iteration   1: 5.298 ±(99.9%) 0.122 ms/op
Iteration   1: 3.868 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.868 ms/op


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.113 ms/op
Iteration   1: 2.333 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.091 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   8.598 ms/op
                 createUser·p0.999:  19.661 ms/op
                 createUser·p0.9999: 19.910 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14020
  mean =      2.333 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 10389 
    [ 2.500,  3.750) = 3181 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.396 ms/op
     p(99.0000) =      8.598 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     19.910 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.077 ms/op
Iteration   1: 2.092 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.097 ms/op
                 existUser·p0.90:   2.658 ms/op
                 existUser·p0.95:   2.867 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  12.361 ms/op
                 existUser·p0.9999: 14.136 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15391
  mean =      2.092 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 936 
    [ 1.250,  2.500) = 11756 
    [ 2.500,  3.750) = 2577 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =     12.361 ms/op
     p(99.9900) =     14.136 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.502 ±(99.9%) 0.112 ms/op
Iteration   1: 2.163 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.855 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.247 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14898
  mean =      2.163 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 10976 
    [ 2.500,  3.750) = 3647 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 64 
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
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.247 ms/op
     p(99.9990) =     13.255 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.142 ms/op
Iteration   1: 3.349 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.285 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.544 ms/op
                 listUser·p0.99:   6.448 ms/op
                 listUser·p0.999:  9.802 ms/op
                 listUser·p0.9999: 12.386 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9546
  mean =      3.349 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 726 
    [ 2.500,  3.750) = 6333 
    [ 3.750,  5.000) = 2232 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.544 ms/op
     p(99.0000) =      6.448 ms/op
     p(99.9000) =      9.802 ms/op
     p(99.9900) =     12.386 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.034          ops/ms
ClientSimple.existUser                       thrpt         11.955          ops/ms
ClientSimple.getUser                         thrpt         13.264          ops/ms
ClientSimple.listUser                        thrpt          8.431          ops/ms
ClientSimple.createUser                       avgt          2.310           ms/op
ClientSimple.existUser                        avgt          2.196           ms/op
ClientSimple.getUser                          avgt          1.901           ms/op
ClientSimple.listUser                         avgt          3.868           ms/op
ClientSimple.createUser                     sample  14020   2.333 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.791           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.091           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.396           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.598           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.661           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.910           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.923           ms/op
ClientSimple.existUser                      sample  15391   2.092 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.549           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.867           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.564           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.361           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.136           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.189           ms/op
ClientSimple.getUser                        sample  14898   2.163 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.529           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.060           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.621           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.247           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.255           ms/op
ClientSimple.listUser                       sample   9546   3.349 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.124           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.285           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.544           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.448           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.802           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.386           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.386           ms/op

Benchmark result is saved to 1725732743493.json
