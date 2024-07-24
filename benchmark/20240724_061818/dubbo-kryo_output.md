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
# Warmup Iteration   1: 1.671 ops/ms
Iteration   1: 6.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.798 ops/ms


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
# Warmup Iteration   1: 6.432 ops/ms
Iteration   1: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.548 ops/ms


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
# Warmup Iteration   1: 6.895 ops/ms
Iteration   1: 14.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.412 ops/ms


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
# Warmup Iteration   1: 5.860 ops/ms
Iteration   1: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.878 ops/ms


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.092 ms/op
Iteration   1: 2.159 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.159 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.065 ms/op
Iteration   1: 2.072 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.072 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.051 ms/op
Iteration   1: 2.133 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.133 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.094 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.025 ms/op


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.108 ms/op
Iteration   1: 2.193 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  13.442 ms/op
                 createUser·p0.9999: 14.223 ms/op
                 createUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14571
  mean =      2.193 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 12217 
    [ 2.500,  3.750) = 1761 
    [ 3.750,  5.000) = 156 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.442 ms/op
     p(99.9900) =     14.223 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 2.895 ±(99.9%) 0.067 ms/op
Iteration   1: 1.909 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.542 ms/op
                 existUser·p0.99:   4.755 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 12.920 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16729
  mean =      1.909 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 712 
    [ 1.250,  2.500) = 15051 
    [ 2.500,  3.750) = 735 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.542 ms/op
     p(99.0000) =      4.755 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     12.920 ms/op
     p(99.9990) =     13.042 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.099 ms/op
Iteration   1: 2.253 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.208 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  16.007 ms/op
                 getUser·p0.9999: 16.909 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14201
  mean =      2.253 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 10892 
    [ 2.500,  3.750) = 3106 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.208 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     16.909 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.107 ms/op
Iteration   1: 3.260 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.024 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9819
  mean =      3.260 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 151 
    [ 2.500,  5.000) = 9549 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.024 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.798          ops/ms
ClientSimple.existUser                       thrpt         10.548          ops/ms
ClientSimple.getUser                         thrpt         14.412          ops/ms
ClientSimple.listUser                        thrpt          7.878          ops/ms
ClientSimple.createUser                       avgt          2.159           ms/op
ClientSimple.existUser                        avgt          2.072           ms/op
ClientSimple.getUser                          avgt          2.133           ms/op
ClientSimple.listUser                         avgt          3.025           ms/op
ClientSimple.createUser                     sample  14571   2.193 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.732           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.170           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.652           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.442           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.223           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.238           ms/op
ClientSimple.existUser                      sample  16729   1.909 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.625           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.542           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.755           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.337           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.920           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.042           ms/op
ClientSimple.getUser                        sample  14201   2.253 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.922           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.208           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.789           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.007           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.909           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.039           ms/op
ClientSimple.listUser                       sample   9819   3.260 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.257           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.024           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.266           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.627           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.627           ms/op

Benchmark result is saved to 1721801635896.json
