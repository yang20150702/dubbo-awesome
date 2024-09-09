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
# Warmup Iteration   1: 1.927 ops/ms
Iteration   1: 7.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.621 ops/ms


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
# Warmup Iteration   1: 4.471 ops/ms
Iteration   1: 10.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.419 ops/ms


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
# Warmup Iteration   1: 4.891 ops/ms
Iteration   1: 11.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.131 ops/ms


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
# Warmup Iteration   1: 4.121 ops/ms
Iteration   1: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.139 ops/ms


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.086 ms/op
Iteration   1: 2.141 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.141 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.047 ms/op
Iteration   1: 1.766 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.766 ms/op


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
# Warmup Iteration   1: 3.431 ±(99.9%) 0.074 ms/op
Iteration   1: 1.763 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.763 ms/op


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.089 ms/op
Iteration   1: 3.277 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.277 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.095 ms/op
Iteration   1: 2.144 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.892 ms/op
                 createUser·p0.99:   4.764 ms/op
                 createUser·p0.999:  20.878 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14846
  mean =      2.144 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12724 
    [ 2.500,  5.000) = 1986 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      4.764 ms/op
     p(99.9000) =     20.878 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.085 ms/op
Iteration   1: 2.165 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.210 ms/op
                 existUser·p0.50:   2.195 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   3.762 ms/op
                 existUser·p0.999:  14.418 ms/op
                 existUser·p0.9999: 15.296 ms/op
                 existUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14760
  mean =      2.165 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 289 
    [ 1.250,  2.500) = 11984 
    [ 2.500,  3.750) = 2339 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.210 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.762 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     15.296 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.121 ms/op
Iteration   1: 1.998 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.908 ms/op
                 getUser·p0.99:   3.819 ms/op
                 getUser·p0.999:  13.730 ms/op
                 getUser·p0.9999: 14.031 ms/op
                 getUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15955
  mean =      1.998 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 13522 
    [ 2.500,  3.750) = 2197 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      3.819 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     14.031 ms/op
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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.732 ±(99.9%) 0.144 ms/op
Iteration   1: 3.382 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.174 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.041 ms/op
                 listUser·p0.999:  15.183 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9455
  mean =      3.382 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 704 
    [ 2.500,  3.750) = 6092 
    [ 3.750,  5.000) = 2343 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.041 ms/op
     p(99.9000) =     15.183 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.621          ops/ms
ClientSimple.existUser                       thrpt         10.419          ops/ms
ClientSimple.getUser                         thrpt         11.131          ops/ms
ClientSimple.listUser                        thrpt          8.139          ops/ms
ClientSimple.createUser                       avgt          2.141           ms/op
ClientSimple.existUser                        avgt          1.766           ms/op
ClientSimple.getUser                          avgt          1.763           ms/op
ClientSimple.listUser                         avgt          3.277           ms/op
ClientSimple.createUser                     sample  14846   2.144 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.738           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.764           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.878           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.463           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.463           ms/op
ClientSimple.existUser                      sample  14760   2.165 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.210           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.762           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.296           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.319           ms/op
ClientSimple.getUser                        sample  15955   1.998 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.541           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.819           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.730           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.031           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.041           ms/op
ClientSimple.listUser                       sample   9455   3.382 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.861           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.174           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.041           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.183           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.679           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.679           ms/op

Benchmark result is saved to 1725862519446.json
