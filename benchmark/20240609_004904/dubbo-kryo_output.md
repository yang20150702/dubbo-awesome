# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
Iteration   1: 6.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.162 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.118 ops/ms
Iteration   1: 11.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.807 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.463 ops/ms
Iteration   1: 13.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.431 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.837 ops/ms
Iteration   1: 8.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.828 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.511 ±(99.9%) 0.071 ms/op
Iteration   1: 2.213 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.213 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.038 ±(99.9%) 0.046 ms/op
Iteration   1: 2.054 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.054 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.121 ±(99.9%) 0.051 ms/op
Iteration   1: 1.837 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.068 ms/op
Iteration   1: 3.089 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.089 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.177 ±(99.9%) 0.068 ms/op
Iteration   1: 2.472 ±(99.9%) 0.082 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.180 ms/op
                 createUser·p0.99:   8.351 ms/op
                 createUser·p0.999:  55.055 ms/op
                 createUser·p0.9999: 55.509 ms/op
                 createUser·p1.00:   55.509 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12930
  mean =      2.472 ±(99.9%) 0.082 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12642 
    [ 5.000, 10.000) = 192 
    [10.000, 15.000) = 64 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.180 ms/op
     p(99.0000) =      8.351 ms/op
     p(99.9000) =     55.055 ms/op
     p(99.9900) =     55.509 ms/op
     p(99.9990) =     55.509 ms/op
     p(99.9999) =     55.509 ms/op
    p(100.0000) =     55.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ±(99.9%) 0.074 ms/op
Iteration   1: 1.848 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.468 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   3.060 ms/op
                 existUser·p0.999:  17.620 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17291
  mean =      1.848 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 789 
    [ 1.250,  2.500) = 15803 
    [ 2.500,  3.750) = 581 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.060 ms/op
     p(99.9000) =     17.620 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.244 ±(99.9%) 0.080 ms/op
Iteration   1: 2.150 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   3.458 ms/op
                 getUser·p0.999:  14.516 ms/op
                 getUser·p0.9999: 14.846 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14872
  mean =      2.150 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 223 
    [ 1.250,  2.500) = 10638 
    [ 2.500,  3.750) = 3907 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.458 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     14.846 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.580 ±(99.9%) 0.116 ms/op
Iteration   1: 3.324 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.144 ms/op
                 listUser·p0.999:  15.819 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9618
  mean =      3.324 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1796 
    [ 2.500,  3.750) = 5284 
    [ 3.750,  5.000) = 2329 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     15.819 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.162          ops/ms
ClientSimple.existUser                       thrpt         11.807          ops/ms
ClientSimple.getUser                         thrpt         13.431          ops/ms
ClientSimple.listUser                        thrpt          8.828          ops/ms
ClientSimple.createUser                       avgt          2.213           ms/op
ClientSimple.existUser                        avgt          2.054           ms/op
ClientSimple.getUser                          avgt          1.837           ms/op
ClientSimple.listUser                         avgt          3.089           ms/op
ClientSimple.createUser                     sample  12930   2.472 ± 0.082   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.803           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.180           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.351           ms/op
ClientSimple.createUser:createUser·p0.999   sample         55.055           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         55.509           ms/op
ClientSimple.createUser:createUser·p1.00    sample         55.509           ms/op
ClientSimple.existUser                      sample  17291   1.848 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.468           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.060           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.620           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.727           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.727           ms/op
ClientSimple.getUser                        sample  14872   2.150 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.484           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.458           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.516           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.846           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.926           ms/op
ClientSimple.listUser                       sample   9618   3.324 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.214           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.144           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.819           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.597           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.597           ms/op

Benchmark result is saved to 1717893893660.json
