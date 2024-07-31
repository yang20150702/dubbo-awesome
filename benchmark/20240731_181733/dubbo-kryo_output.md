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
# Warmup Iteration   1: 1.345 ops/ms
Iteration   1: 6.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.163 ops/ms


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
# Warmup Iteration   1: 5.923 ops/ms
Iteration   1: 12.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.592 ops/ms


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
# Warmup Iteration   1: 5.773 ops/ms
Iteration   1: 11.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.951 ops/ms


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
# Warmup Iteration   1: 4.379 ops/ms
Iteration   1: 8.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.322 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.083 ms/op
Iteration   1: 2.286 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.286 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.055 ms/op
Iteration   1: 1.830 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.830 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.066 ms/op
Iteration   1: 2.268 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.268 ms/op


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.107 ms/op
Iteration   1: 3.404 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.404 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.098 ms/op
Iteration   1: 2.498 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.409 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.343 ms/op
                 createUser·p0.99:   11.719 ms/op
                 createUser·p0.999:  22.745 ms/op
                 createUser·p0.9999: 23.682 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12874
  mean =      2.498 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9882 
    [ 2.500,  5.000) = 2675 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.343 ms/op
     p(99.0000) =     11.719 ms/op
     p(99.9000) =     22.745 ms/op
     p(99.9900) =     23.682 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.107 ms/op
Iteration   1: 1.889 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  10.635 ms/op
                 existUser·p0.9999: 10.912 ms/op
                 existUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16917
  mean =      1.889 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 16137 
    [ 2.500,  3.750) = 488 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     10.635 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     10.912 ms/op
     p(99.9999) =     10.912 ms/op
    p(100.0000) =     10.912 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.091 ms/op
Iteration   1: 2.296 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   2.179 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.959 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  17.597 ms/op
                 getUser·p0.9999: 17.839 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13973
  mean =      2.296 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 10902 
    [ 2.500,  3.750) = 2851 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.959 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =     17.597 ms/op
     p(99.9900) =     17.839 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 5.197 ±(99.9%) 0.154 ms/op
Iteration   1: 3.694 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 14.516 ms/op
                 listUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8650
  mean =      3.694 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 338 
    [ 2.500,  3.750) = 4683 
    [ 3.750,  5.000) = 3231 
    [ 5.000,  6.250) = 242 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     14.516 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.163          ops/ms
ClientSimple.existUser                       thrpt         12.592          ops/ms
ClientSimple.getUser                         thrpt         11.951          ops/ms
ClientSimple.listUser                        thrpt          8.322          ops/ms
ClientSimple.createUser                       avgt          2.286           ms/op
ClientSimple.existUser                        avgt          1.830           ms/op
ClientSimple.getUser                          avgt          2.268           ms/op
ClientSimple.listUser                         avgt          3.404           ms/op
ClientSimple.createUser                     sample  12874   2.498 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.409           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.343           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.719           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.745           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.682           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.691           ms/op
ClientSimple.existUser                      sample  16917   1.889 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.634           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.635           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.912           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.912           ms/op
ClientSimple.getUser                        sample  13973   2.296 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.488           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.179           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.959           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.826           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.597           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.839           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.891           ms/op
ClientSimple.listUser                       sample   8650   3.694 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.233           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.176           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.205           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.516           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.516           ms/op

Benchmark result is saved to 1722449588103.json
