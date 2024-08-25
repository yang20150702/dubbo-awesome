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
# Warmup Iteration   1: 1.831 ops/ms
Iteration   1: 7.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.477 ops/ms


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
# Warmup Iteration   1: 4.615 ops/ms
Iteration   1: 10.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.434 ops/ms


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
# Warmup Iteration   1: 5.667 ops/ms
Iteration   1: 13.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.313 ops/ms


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
# Warmup Iteration   1: 6.096 ops/ms
Iteration   1: 8.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.411 ops/ms


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.075 ms/op
Iteration   1: 2.206 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.206 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.047 ms/op
Iteration   1: 1.824 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.824 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.057 ms/op
Iteration   1: 1.779 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.779 ms/op


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.082 ms/op
Iteration   1: 3.270 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.270 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.091 ms/op
Iteration   1: 2.289 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   9.866 ms/op
                 createUser·p0.999:  30.985 ms/op
                 createUser·p0.9999: 33.579 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14280
  mean =      2.289 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11739 
    [ 2.500,  5.000) = 2319 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      9.866 ms/op
     p(99.9000) =     30.985 ms/op
     p(99.9900) =     33.579 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 2.816 ±(99.9%) 0.071 ms/op
Iteration   1: 1.962 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   1.812 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  24.576 ms/op
                 existUser·p0.9999: 25.190 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16303
  mean =      1.962 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15215 
    [ 2.500,  5.000) = 1024 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     25.190 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.088 ms/op
Iteration   1: 2.290 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.220 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.141 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  12.027 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13943
  mean =      2.290 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 9491 
    [ 2.500,  3.750) = 4143 
    [ 3.750,  5.000) = 175 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 2 
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
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.141 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =     12.027 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.129 ms/op
Iteration   1: 3.140 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.640 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.318 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 18.740 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10191
  mean =      3.140 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 2364 
    [ 2.500,  3.750) = 5788 
    [ 3.750,  5.000) = 1843 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.318 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     18.740 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.477          ops/ms
ClientSimple.existUser                       thrpt         10.434          ops/ms
ClientSimple.getUser                         thrpt         13.313          ops/ms
ClientSimple.listUser                        thrpt          8.411          ops/ms
ClientSimple.createUser                       avgt          2.206           ms/op
ClientSimple.existUser                        avgt          1.824           ms/op
ClientSimple.getUser                          avgt          1.779           ms/op
ClientSimple.listUser                         avgt          3.270           ms/op
ClientSimple.createUser                     sample  14280   2.289 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.866           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.985           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.579           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.603           ms/op
ClientSimple.existUser                      sample  16303   1.962 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.699           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.812           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.182           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.576           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.190           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.231           ms/op
ClientSimple.getUser                        sample  13943   2.290 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.821           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.220           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.141           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.014           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.027           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.190           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.222           ms/op
ClientSimple.listUser                       sample  10191   3.140 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.640           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.892           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.318           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.663           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.740           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.743           ms/op

Benchmark result is saved to 1724588161322.json
