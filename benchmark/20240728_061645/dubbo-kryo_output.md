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
# Warmup Iteration   1: 1.838 ops/ms
Iteration   1: 7.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.405 ops/ms


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
# Warmup Iteration   1: 5.306 ops/ms
Iteration   1: 14.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.454 ops/ms


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
# Warmup Iteration   1: 5.958 ops/ms
Iteration   1: 13.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.659 ops/ms


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
# Warmup Iteration   1: 5.244 ops/ms
Iteration   1: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.899 ops/ms


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.082 ms/op
Iteration   1: 2.248 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.248 ms/op


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
# Warmup Iteration   1: 2.756 ±(99.9%) 0.046 ms/op
Iteration   1: 1.960 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.960 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.075 ms/op
Iteration   1: 1.776 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.776 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.099 ms/op
Iteration   1: 3.253 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.253 ms/op


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.077 ms/op
Iteration   1: 2.247 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.420 ms/op
                 createUser·p0.99:   7.665 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 14.942 ms/op
                 createUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14222
  mean =      2.247 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 10863 
    [ 2.500,  3.750) = 2799 
    [ 3.750,  5.000) = 232 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.420 ms/op
     p(99.0000) =      7.665 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.081 ms/op
Iteration   1: 1.859 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.435 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   2.867 ms/op
                 existUser·p0.999:  12.363 ms/op
                 existUser·p0.9999: 13.428 ms/op
                 existUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17200
  mean =      1.859 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 428 
    [ 1.250,  2.500) = 15978 
    [ 2.500,  3.750) = 758 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      2.867 ms/op
     p(99.9000) =     12.363 ms/op
     p(99.9900) =     13.428 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.086 ms/op
Iteration   1: 1.796 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   1.722 ms/op
                 getUser·p0.90:   2.122 ms/op
                 getUser·p0.95:   2.277 ms/op
                 getUser·p0.99:   3.173 ms/op
                 getUser·p0.999:  14.287 ms/op
                 getUser·p0.9999: 14.372 ms/op
                 getUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17803
  mean =      1.796 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 666 
    [ 1.250,  2.500) = 16706 
    [ 2.500,  3.750) = 300 
    [ 3.750,  5.000) = 1 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.277 ms/op
     p(99.0000) =      3.173 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     14.372 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.107 ms/op
Iteration   1: 3.106 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.128 ms/op
                 listUser·p0.999:  5.879 ms/op
                 listUser·p0.9999: 7.980 ms/op
                 listUser·p1.00:   7.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10300
  mean =      3.106 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 31 
    [1.500, 2.000) = 132 
    [2.000, 2.500) = 1571 
    [2.500, 3.000) = 4105 
    [3.000, 3.500) = 1428 
    [3.500, 4.000) = 1806 
    [4.000, 4.500) = 953 
    [4.500, 5.000) = 151 
    [5.000, 5.500) = 47 
    [5.500, 6.000) = 69 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      5.879 ms/op
     p(99.9900) =      7.980 ms/op
     p(99.9990) =      7.987 ms/op
     p(99.9999) =      7.987 ms/op
    p(100.0000) =      7.987 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.405          ops/ms
ClientSimple.existUser                       thrpt         14.454          ops/ms
ClientSimple.getUser                         thrpt         13.659          ops/ms
ClientSimple.listUser                        thrpt          7.899          ops/ms
ClientSimple.createUser                       avgt          2.248           ms/op
ClientSimple.existUser                        avgt          1.960           ms/op
ClientSimple.getUser                          avgt          1.776           ms/op
ClientSimple.listUser                         avgt          3.253           ms/op
ClientSimple.createUser                     sample  14222   2.247 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.844           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.420           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.665           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.778           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.942           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.942           ms/op
ClientSimple.existUser                      sample  17200   1.859 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.435           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.867           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.363           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.428           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.664           ms/op
ClientSimple.getUser                        sample  17803   1.796 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.546           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.722           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.173           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.287           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.372           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.385           ms/op
ClientSimple.listUser                       sample  10300   3.106 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.029           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.896           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.879           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.980           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.987           ms/op

Benchmark result is saved to 1722147147535.json
