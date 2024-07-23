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
# Warmup Iteration   1: 1.654 ops/ms
Iteration   1: 7.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.035 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.435 ops/ms
Iteration   1: 12.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.257 ops/ms


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
# Warmup Iteration   1: 5.844 ops/ms
Iteration   1: 12.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.885 ops/ms


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
# Warmup Iteration   1: 4.261 ops/ms
Iteration   1: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.069 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.081 ms/op
Iteration   1: 2.056 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.056 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.385 ±(99.9%) 0.059 ms/op
Iteration   1: 1.831 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.831 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.205 ±(99.9%) 0.052 ms/op
Iteration   1: 2.146 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.146 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.503 ±(99.9%) 0.109 ms/op
Iteration   1: 3.446 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.446 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.107 ms/op
Iteration   1: 2.295 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   4.378 ms/op
                 createUser·p0.999:  16.371 ms/op
                 createUser·p0.9999: 24.715 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13926
  mean =      2.295 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10054 
    [ 2.500,  5.000) = 3762 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      4.378 ms/op
     p(99.9000) =     16.371 ms/op
     p(99.9900) =     24.715 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 2.898 ±(99.9%) 0.062 ms/op
Iteration   1: 1.765 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.209 ms/op
                 existUser·p0.50:   1.540 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.423 ms/op
                 existUser·p0.999:  18.349 ms/op
                 existUser·p0.9999: 18.987 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18515
  mean =      1.765 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 961 
    [ 1.250,  2.500) = 15897 
    [ 2.500,  3.750) = 1503 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.209 ms/op
     p(50.0000) =      1.540 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.423 ms/op
     p(99.9000) =     18.349 ms/op
     p(99.9900) =     18.987 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.082 ms/op
Iteration   1: 1.986 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.462 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   3.248 ms/op
                 getUser·p0.999:  7.691 ms/op
                 getUser·p0.9999: 8.988 ms/op
                 getUser·p1.00:   9.880 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16045
  mean =      1.986 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 116 
    [ 1.000,  2.000) = 8276 
    [ 2.000,  3.000) = 7306 
    [ 3.000,  4.000) = 256 
    [ 4.000,  5.000) = 13 
    [ 5.000,  6.000) = 27 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 48 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.248 ms/op
     p(99.9000) =      7.691 ms/op
     p(99.9900) =      8.988 ms/op
     p(99.9990) =      9.880 ms/op
     p(99.9999) =      9.880 ms/op
    p(100.0000) =      9.880 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.117 ms/op
Iteration   1: 3.400 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   3.236 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.438 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  29.150 ms/op
                 listUser·p0.9999: 32.113 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9404
  mean =      3.400 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 808 
    [ 2.500,  5.000) = 8330 
    [ 5.000,  7.500) = 207 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.438 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     29.150 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.035          ops/ms
ClientSimple.existUser                       thrpt         12.257          ops/ms
ClientSimple.getUser                         thrpt         12.885          ops/ms
ClientSimple.listUser                        thrpt          8.069          ops/ms
ClientSimple.createUser                       avgt          2.056           ms/op
ClientSimple.existUser                        avgt          1.831           ms/op
ClientSimple.getUser                          avgt          2.146           ms/op
ClientSimple.listUser                         avgt          3.446           ms/op
ClientSimple.createUser                     sample  13926   2.295 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.944           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.378           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.371           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.715           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.805           ms/op
ClientSimple.existUser                      sample  18515   1.765 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.209           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.540           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.423           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.349           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.987           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.071           ms/op
ClientSimple.getUser                        sample  16045   1.986 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.462           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.248           ms/op
ClientSimple.getUser:getUser·p0.999         sample          7.691           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          8.988           ms/op
ClientSimple.getUser:getUser·p1.00          sample          9.880           ms/op
ClientSimple.listUser                       sample   9404   3.400 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.728           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.236           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.438           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.150           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.113           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.113           ms/op

Benchmark result is saved to 1721715214062.json
