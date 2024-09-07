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
# Warmup Iteration   1: 2.155 ops/ms
Iteration   1: 7.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.499 ops/ms


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
# Warmup Iteration   1: 6.262 ops/ms
Iteration   1: 12.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.198 ops/ms


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
# Warmup Iteration   1: 5.817 ops/ms
Iteration   1: 12.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.594 ops/ms


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
# Warmup Iteration   1: 4.918 ops/ms
Iteration   1: 9.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.130 ops/ms


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.073 ms/op
Iteration   1: 2.229 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.051 ms/op
Iteration   1: 1.740 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.740 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.059 ms/op
Iteration   1: 1.733 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.733 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.098 ms/op
Iteration   1: 3.180 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.180 ms/op


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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.098 ms/op
Iteration   1: 2.093 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   1.903 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.763 ms/op
                 createUser·p0.99:   5.573 ms/op
                 createUser·p0.999:  13.679 ms/op
                 createUser·p0.9999: 14.491 ms/op
                 createUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15266
  mean =      2.093 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 13618 
    [ 2.500,  3.750) = 1325 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.763 ms/op
     p(99.0000) =      5.573 ms/op
     p(99.9000) =     13.679 ms/op
     p(99.9900) =     14.491 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.055 ±(99.9%) 0.092 ms/op
Iteration   1: 2.009 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 18.705 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15916
  mean =      2.009 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 13900 
    [ 2.500,  3.750) = 1660 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     18.705 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.082 ms/op
Iteration   1: 2.187 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.706 ms/op
                 getUser·p0.999:  20.362 ms/op
                 getUser·p0.9999: 20.811 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14606
  mean =      2.187 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12425 
    [ 2.500,  5.000) = 2117 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.706 ms/op
     p(99.9000) =     20.362 ms/op
     p(99.9900) =     20.811 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.131 ms/op
Iteration   1: 3.379 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.236 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9431
  mean =      3.379 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 680 
    [ 2.500,  3.750) = 6370 
    [ 3.750,  5.000) = 2222 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.499          ops/ms
ClientSimple.existUser                       thrpt         12.198          ops/ms
ClientSimple.getUser                         thrpt         12.594          ops/ms
ClientSimple.listUser                        thrpt          9.130          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          1.740           ms/op
ClientSimple.getUser                          avgt          1.733           ms/op
ClientSimple.listUser                         avgt          3.180           ms/op
ClientSimple.createUser                     sample  15266   2.093 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.167           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.903           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.763           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.573           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.679           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.491           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.500           ms/op
ClientSimple.existUser                      sample  15916   2.009 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.717           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.301           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.153           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.705           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.743           ms/op
ClientSimple.getUser                        sample  14606   2.187 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.785           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.706           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.362           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.811           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.037           ms/op
ClientSimple.listUser                       sample   9431   3.379 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.133           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.236           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.464           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.022           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.874           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.874           ms/op

Benchmark result is saved to 1725669892808.json
