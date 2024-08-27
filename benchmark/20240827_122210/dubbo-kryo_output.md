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
# Warmup Iteration   1: 1.051 ops/ms
Iteration   1: 6.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.715 ops/ms


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
# Warmup Iteration   1: 6.216 ops/ms
Iteration   1: 13.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.438 ops/ms


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
# Warmup Iteration   1: 5.686 ops/ms
Iteration   1: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.797 ops/ms


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
# Warmup Iteration   1: 5.254 ops/ms
Iteration   1: 8.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.724 ops/ms


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.074 ms/op
Iteration   1: 1.893 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.893 ms/op


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
# Warmup Iteration   1: 3.022 ±(99.9%) 0.047 ms/op
Iteration   1: 2.037 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.037 ms/op


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
# Warmup Iteration   1: 3.159 ±(99.9%) 0.058 ms/op
Iteration   1: 1.935 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.086 ms/op
Iteration   1: 3.158 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.158 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.085 ms/op
Iteration   1: 2.094 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.404 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.753 ms/op
                 createUser·p0.99:   4.699 ms/op
                 createUser·p0.999:  13.873 ms/op
                 createUser·p0.9999: 14.834 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15254
  mean =      2.094 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 423 
    [ 1.250,  2.500) = 12796 
    [ 2.500,  3.750) = 1870 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      4.699 ms/op
     p(99.9000) =     13.873 ms/op
     p(99.9900) =     14.834 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.063 ms/op
Iteration   1: 1.737 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.347 ms/op
                 existUser·p0.50:   1.567 ms/op
                 existUser·p0.90:   2.079 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   3.779 ms/op
                 existUser·p0.999:  19.137 ms/op
                 existUser·p0.9999: 19.310 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18514
  mean =      1.737 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 17685 
    [ 2.500,  3.750) = 220 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      1.567 ms/op
     p(90.0000) =      2.079 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      3.779 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     19.310 ms/op
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
# Warmup Iteration   1: 3.231 ±(99.9%) 0.077 ms/op
Iteration   1: 2.175 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.079 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 19.334 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14694
  mean =      2.175 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 256 
    [ 1.250,  2.500) = 11467 
    [ 2.500,  3.750) = 2814 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     19.334 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.127 ms/op
Iteration   1: 3.377 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.265 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.814 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9402
  mean =      3.377 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 759 
    [ 2.500,  3.750) = 6087 
    [ 3.750,  5.000) = 2323 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.814 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.715          ops/ms
ClientSimple.existUser                       thrpt         13.438          ops/ms
ClientSimple.getUser                         thrpt         12.797          ops/ms
ClientSimple.listUser                        thrpt          8.724          ops/ms
ClientSimple.createUser                       avgt          1.893           ms/op
ClientSimple.existUser                        avgt          2.037           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.158           ms/op
ClientSimple.createUser                     sample  15254   2.094 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.404           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.699           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.873           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.834           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.860           ms/op
ClientSimple.existUser                      sample  18514   1.737 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.347           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.567           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.079           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.779           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.137           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.310           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.366           ms/op
ClientSimple.getUser                        sample  14694   2.175 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.558           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.079           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.071           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.481           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.334           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.595           ms/op
ClientSimple.listUser                       sample   9402   3.377 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.257           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.265           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.116           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.814           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.400           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.890           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.890           ms/op

Benchmark result is saved to 1724761072936.json
