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
# Warmup Iteration   1: 2.175 ops/ms
Iteration   1: 8.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.312 ops/ms


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
# Warmup Iteration   1: 6.732 ops/ms
Iteration   1: 14.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.449 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ops/ms
Iteration   1: 14.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.931 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.412 ops/ms
Iteration   1: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.602 ops/ms


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.060 ms/op
Iteration   1: 2.129 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.129 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.047 ms/op
Iteration   1: 2.059 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.059 ms/op


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
# Warmup Iteration   1: 2.944 ±(99.9%) 0.076 ms/op
Iteration   1: 1.695 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.695 ms/op


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.092 ms/op
Iteration   1: 3.183 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.183 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.083 ms/op
Iteration   1: 2.106 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.478 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   5.983 ms/op
                 createUser·p0.999:  31.156 ms/op
                 createUser·p0.9999: 34.761 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15182
  mean =      2.106 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13725 
    [ 2.500,  5.000) = 1185 
    [ 5.000,  7.500) = 154 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      5.983 ms/op
     p(99.9000) =     31.156 ms/op
     p(99.9900) =     34.761 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ±(99.9%) 0.070 ms/op
Iteration   1: 1.813 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.295 ms/op
                 existUser·p0.50:   1.649 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  18.645 ms/op
                 existUser·p0.9999: 18.678 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17628
  mean =      1.813 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1260 
    [ 1.250,  2.500) = 15360 
    [ 2.500,  3.750) = 802 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      1.649 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.170 ±(99.9%) 0.074 ms/op
Iteration   1: 1.710 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   1.614 ms/op
                 getUser·p0.90:   2.114 ms/op
                 getUser·p0.95:   2.335 ms/op
                 getUser·p0.99:   2.687 ms/op
                 getUser·p0.999:  12.638 ms/op
                 getUser·p0.9999: 13.752 ms/op
                 getUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18832
  mean =      1.710 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 324 
    [ 1.250,  2.500) = 18086 
    [ 2.500,  3.750) = 313 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.114 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      2.687 ms/op
     p(99.9000) =     12.638 ms/op
     p(99.9900) =     13.752 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.020 ±(99.9%) 0.199 ms/op
Iteration   1: 3.483 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.105 ms/op
                 listUser·p0.999:  13.552 ms/op
                 listUser·p0.9999: 14.418 ms/op
                 listUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9273
  mean =      3.483 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 699 
    [ 2.500,  3.750) = 6279 
    [ 3.750,  5.000) = 2052 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.105 ms/op
     p(99.9000) =     13.552 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.312          ops/ms
ClientSimple.existUser                       thrpt         14.449          ops/ms
ClientSimple.getUser                         thrpt         14.931          ops/ms
ClientSimple.listUser                        thrpt          8.602          ops/ms
ClientSimple.createUser                       avgt          2.129           ms/op
ClientSimple.existUser                        avgt          2.059           ms/op
ClientSimple.getUser                          avgt          1.695           ms/op
ClientSimple.listUser                         avgt          3.183           ms/op
ClientSimple.createUser                     sample  15182   2.106 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.499           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.478           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.983           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.156           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.761           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.931           ms/op
ClientSimple.existUser                      sample  17628   1.813 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.295           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.649           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.391           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.645           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.678           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.678           ms/op
ClientSimple.getUser                        sample  18832   1.710 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.636           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.614           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.638           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.752           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.041           ms/op
ClientSimple.listUser                       sample   9273   3.483 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.829           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.105           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.552           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.418           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.418           ms/op

Benchmark result is saved to 1723400020538.json
