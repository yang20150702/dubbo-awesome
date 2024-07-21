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
# Warmup Iteration   1: 1.655 ops/ms
Iteration   1: 6.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.623 ops/ms


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
# Warmup Iteration   1: 6.297 ops/ms
Iteration   1: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.848 ops/ms


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
# Warmup Iteration   1: 6.127 ops/ms
Iteration   1: 13.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.295 ops/ms


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
# Warmup Iteration   1: 4.505 ops/ms
Iteration   1: 7.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.865 ops/ms


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.077 ms/op
Iteration   1: 2.192 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.192 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.056 ms/op
Iteration   1: 2.159 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ±(99.9%) 0.079 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.443 ms/op


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.087 ms/op
Iteration   1: 3.250 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.250 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.084 ms/op
Iteration   1: 2.244 ±(99.9%) 0.067 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   2.048 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  37.984 ms/op
                 createUser·p0.9999: 39.846 ms/op
                 createUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14409
  mean =      2.244 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12491 
    [ 2.500,  5.000) = 1693 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     37.984 ms/op
     p(99.9900) =     39.846 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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
# Warmup Iteration   1: 2.951 ±(99.9%) 0.067 ms/op
Iteration   1: 1.814 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   3.319 ms/op
                 existUser·p0.999:  12.834 ms/op
                 existUser·p0.9999: 13.057 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17661
  mean =      1.814 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 402 
    [ 1.250,  2.500) = 16410 
    [ 2.500,  3.750) = 738 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      3.319 ms/op
     p(99.9000) =     12.834 ms/op
     p(99.9900) =     13.057 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.105 ms/op
Iteration   1: 2.221 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.216 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  12.704 ms/op
                 getUser·p0.9999: 12.911 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14579
  mean =      2.221 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 10762 
    [ 2.500,  3.750) = 3436 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.216 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =     12.704 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.123 ms/op
Iteration   1: 3.496 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.318 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.869 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 14.123 ms/op
                 listUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9250
  mean =      3.496 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 424 
    [ 2.500,  3.750) = 5360 
    [ 3.750,  5.000) = 3218 
    [ 5.000,  6.250) = 167 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.869 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.623          ops/ms
ClientSimple.existUser                       thrpt         12.848          ops/ms
ClientSimple.getUser                         thrpt         13.295          ops/ms
ClientSimple.listUser                        thrpt          7.865          ops/ms
ClientSimple.createUser                       avgt          2.192           ms/op
ClientSimple.existUser                        avgt          2.159           ms/op
ClientSimple.getUser                          avgt          2.443           ms/op
ClientSimple.listUser                         avgt          3.250           ms/op
ClientSimple.createUser                     sample  14409   2.244 ± 0.067   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.048           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.699           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.984           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.846           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.846           ms/op
ClientSimple.existUser                      sample  17661   1.814 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.506           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.319           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.834           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.057           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.107           ms/op
ClientSimple.getUser                        sample  14579   2.221 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.216           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.125           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.063           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.704           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.911           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.911           ms/op
ClientSimple.listUser                       sample   9250   3.496 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.057           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.318           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.869           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.976           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.123           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.123           ms/op

Benchmark result is saved to 1721542332569.json
