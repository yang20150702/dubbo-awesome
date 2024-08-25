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
# Warmup Iteration   1: 1.692 ops/ms
Iteration   1: 7.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.186 ops/ms


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
# Warmup Iteration   1: 6.301 ops/ms
Iteration   1: 14.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.037 ops/ms


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
# Warmup Iteration   1: 6.134 ops/ms
Iteration   1: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.819 ops/ms


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
# Warmup Iteration   1: 4.794 ops/ms
Iteration   1: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.711 ops/ms


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.082 ms/op
Iteration   1: 2.244 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.244 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.057 ms/op
Iteration   1: 1.862 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.062 ms/op
Iteration   1: 2.257 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.257 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.157 ms/op
Iteration   1: 3.678 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.678 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.085 ms/op
Iteration   1: 2.324 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   1.958 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.892 ms/op
                 createUser·p0.99:   7.105 ms/op
                 createUser·p0.999:  75.163 ms/op
                 createUser·p0.9999: 97.812 ms/op
                 createUser·p1.00:   97.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13754
  mean =      2.324 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 13660 
    [ 10.000,  20.000) = 40 
    [ 20.000,  30.000) = 11 
    [ 30.000,  40.000) = 4 
    [ 40.000,  50.000) = 9 
    [ 50.000,  60.000) = 6 
    [ 60.000,  70.000) = 6 
    [ 70.000,  80.000) = 8 
    [ 80.000,  90.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      7.105 ms/op
     p(99.9000) =     75.163 ms/op
     p(99.9900) =     97.812 ms/op
     p(99.9990) =     97.911 ms/op
     p(99.9999) =     97.911 ms/op
    p(100.0000) =     97.911 ms/op


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
# Warmup Iteration   1: 2.791 ±(99.9%) 0.065 ms/op
Iteration   1: 1.974 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.527 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  18.632 ms/op
                 existUser·p0.9999: 19.305 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16195
  mean =      1.974 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 991 
    [ 1.250,  2.500) = 13344 
    [ 2.500,  3.750) = 1731 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =     18.632 ms/op
     p(99.9900) =     19.305 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.081 ms/op
Iteration   1: 1.873 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   1.737 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.535 ms/op
                 getUser·p0.99:   3.388 ms/op
                 getUser·p0.999:  12.468 ms/op
                 getUser·p0.9999: 12.815 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17392
  mean =      1.873 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 16339 
    [ 2.500,  3.750) = 881 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.388 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     12.815 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.166 ms/op
Iteration   1: 3.301 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  22.154 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9731
  mean =      3.301 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1794 
    [ 2.500,  5.000) = 7738 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     22.154 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.186          ops/ms
ClientSimple.existUser                       thrpt         14.037          ops/ms
ClientSimple.getUser                         thrpt         12.819          ops/ms
ClientSimple.listUser                        thrpt          8.711          ops/ms
ClientSimple.createUser                       avgt          2.244           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          2.257           ms/op
ClientSimple.listUser                         avgt          3.678           ms/op
ClientSimple.createUser                     sample  13754   2.324 ± 0.106   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.709           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.958           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.105           ms/op
ClientSimple.createUser:createUser·p0.999   sample         75.163           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         97.812           ms/op
ClientSimple.createUser:createUser·p1.00    sample         97.911           ms/op
ClientSimple.existUser                      sample  16195   1.974 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.460           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.498           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.632           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.305           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.366           ms/op
ClientSimple.getUser                        sample  17392   1.873 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.817           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.737           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.388           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.815           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.009           ms/op
ClientSimple.listUser                       sample   9731   3.301 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.748           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.096           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.154           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.527           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.527           ms/op

Benchmark result is saved to 1724609499268.json
