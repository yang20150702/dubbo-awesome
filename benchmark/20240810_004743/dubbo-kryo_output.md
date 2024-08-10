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
# Warmup Iteration   1: 1.836 ops/ms
Iteration   1: 7.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.393 ops/ms


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
# Warmup Iteration   1: 6.760 ops/ms
Iteration   1: 11.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.912 ops/ms


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
# Warmup Iteration   1: 6.113 ops/ms
Iteration   1: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.707 ops/ms


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
# Warmup Iteration   1: 5.719 ops/ms
Iteration   1: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.545 ops/ms


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.086 ms/op
Iteration   1: 2.315 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.315 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.097 ms/op
Iteration   1: 2.047 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.047 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.063 ms/op
Iteration   1: 1.872 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.872 ms/op


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.080 ms/op
Iteration   1: 3.312 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.312 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.091 ms/op
Iteration   1: 2.438 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.475 ms/op
                 createUser·p0.50:   2.277 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  19.297 ms/op
                 createUser·p0.9999: 22.504 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13114
  mean =      2.438 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8703 
    [ 2.500,  5.000) = 4120 
    [ 5.000,  7.500) = 149 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     19.297 ms/op
     p(99.9900) =     22.504 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.100 ms/op
Iteration   1: 1.853 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.314 ms/op
                 existUser·p0.99:   3.260 ms/op
                 existUser·p0.999:  12.123 ms/op
                 existUser·p0.9999: 12.276 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17270
  mean =      1.853 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 16726 
    [ 2.500,  3.750) = 286 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.314 ms/op
     p(99.0000) =      3.260 ms/op
     p(99.9000) =     12.123 ms/op
     p(99.9900) =     12.276 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.076 ms/op
Iteration   1: 1.892 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   1.636 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.355 ms/op
                 getUser·p0.999:  23.495 ms/op
                 getUser·p0.9999: 24.072 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16979
  mean =      1.892 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15295 
    [ 2.500,  5.000) = 1586 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.636 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.355 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     24.072 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 5.001 ±(99.9%) 0.133 ms/op
Iteration   1: 3.189 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  17.394 ms/op
                 listUser·p0.9999: 18.905 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10055
  mean =      3.189 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2143 
    [ 2.500,  3.750) = 5647 
    [ 3.750,  5.000) = 2016 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     17.394 ms/op
     p(99.9900) =     18.905 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.393          ops/ms
ClientSimple.existUser                       thrpt         11.912          ops/ms
ClientSimple.getUser                         thrpt         12.707          ops/ms
ClientSimple.listUser                        thrpt          8.545          ops/ms
ClientSimple.createUser                       avgt          2.315           ms/op
ClientSimple.existUser                        avgt          2.047           ms/op
ClientSimple.getUser                          avgt          1.872           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  13114   2.438 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.475           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.244           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.627           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.297           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.504           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.544           ms/op
ClientSimple.existUser                      sample  17270   1.853 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.759           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.260           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.123           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.276           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.288           ms/op
ClientSimple.getUser                        sample  16979   1.892 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.636           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.355           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.495           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.072           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.117           ms/op
ClientSimple.listUser                       sample  10055   3.189 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.085           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.906           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.394           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.907           ms/op

Benchmark result is saved to 1723250606484.json
