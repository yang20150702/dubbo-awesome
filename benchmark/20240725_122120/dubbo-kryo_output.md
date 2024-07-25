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
# Warmup Iteration   1: 1.826 ops/ms
Iteration   1: 6.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.954 ops/ms


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
# Warmup Iteration   1: 5.558 ops/ms
Iteration   1: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.976 ops/ms


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
# Warmup Iteration   1: 5.315 ops/ms
Iteration   1: 13.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.848 ops/ms


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
# Warmup Iteration   1: 4.056 ops/ms
Iteration   1: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.053 ops/ms


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.080 ms/op
Iteration   1: 2.200 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.200 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.065 ms/op
Iteration   1: 1.792 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.792 ms/op


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
# Warmup Iteration   1: 3.222 ±(99.9%) 0.055 ms/op
Iteration   1: 1.998 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.998 ms/op


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.107 ms/op
Iteration   1: 3.573 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.573 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.107 ms/op
Iteration   1: 2.263 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   8.165 ms/op
                 createUser·p0.999:  15.415 ms/op
                 createUser·p0.9999: 16.298 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14129
  mean =      2.263 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 10675 
    [ 2.500,  3.750) = 2813 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      8.165 ms/op
     p(99.9000) =     15.415 ms/op
     p(99.9900) =     16.298 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.070 ms/op
Iteration   1: 2.123 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.415 ms/op
                 existUser·p0.50:   2.019 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  28.344 ms/op
                 existUser·p0.9999: 29.162 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15105
  mean =      2.123 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13558 
    [ 2.500,  5.000) = 1434 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =     28.344 ms/op
     p(99.9900) =     29.162 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.079 ms/op
Iteration   1: 2.195 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.843 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.041 ms/op
                 getUser·p0.999:  6.179 ms/op
                 getUser·p0.9999: 8.379 ms/op
                 getUser·p1.00:   9.994 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14693
  mean =      2.195 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 13 
    [ 1.000,  2.000) = 6074 
    [ 2.000,  3.000) = 7558 
    [ 3.000,  4.000) = 900 
    [ 4.000,  5.000) = 59 
    [ 5.000,  6.000) = 59 
    [ 6.000,  7.000) = 29 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      4.041 ms/op
     p(99.9000) =      6.179 ms/op
     p(99.9900) =      8.379 ms/op
     p(99.9990) =      9.994 ms/op
     p(99.9999) =      9.994 ms/op
    p(100.0000) =      9.994 ms/op


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.120 ms/op
Iteration   1: 3.823 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.869 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  56.152 ms/op
                 listUser·p0.9999: 62.849 ms/op
                 listUser·p1.00:   62.849 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8372
  mean =      3.823 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8036 
    [ 5.000, 10.000) = 248 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 24 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.869 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     56.152 ms/op
     p(99.9900) =     62.849 ms/op
     p(99.9990) =     62.849 ms/op
     p(99.9999) =     62.849 ms/op
    p(100.0000) =     62.849 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.954          ops/ms
ClientSimple.existUser                       thrpt         12.976          ops/ms
ClientSimple.getUser                         thrpt         13.848          ops/ms
ClientSimple.listUser                        thrpt          8.053          ops/ms
ClientSimple.createUser                       avgt          2.200           ms/op
ClientSimple.existUser                        avgt          1.792           ms/op
ClientSimple.getUser                          avgt          1.998           ms/op
ClientSimple.listUser                         avgt          3.573           ms/op
ClientSimple.createUser                     sample  14129   2.263 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.577           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.117           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.165           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.415           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.298           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.630           ms/op
ClientSimple.existUser                      sample  15105   2.123 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.415           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.019           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.002           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.344           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.162           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.229           ms/op
ClientSimple.getUser                        sample  14693   2.195 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.600           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.041           ms/op
ClientSimple.getUser:getUser·p0.999         sample          6.179           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          8.379           ms/op
ClientSimple.getUser:getUser·p1.00          sample          9.994           ms/op
ClientSimple.listUser                       sample   8372   3.823 ± 0.123   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.957           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.584           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.869           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.043           ms/op
ClientSimple.listUser:listUser·p0.999       sample         56.152           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         62.849           ms/op
ClientSimple.listUser:listUser·p1.00        sample         62.849           ms/op

Benchmark result is saved to 1721909832823.json
