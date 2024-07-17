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
# Warmup Iteration   1: 1.798 ops/ms
Iteration   1: 6.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.430 ops/ms


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
# Warmup Iteration   1: 5.797 ops/ms
Iteration   1: 14.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.467 ops/ms


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
# Warmup Iteration   1: 4.967 ops/ms
Iteration   1: 9.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.936 ops/ms


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
# Warmup Iteration   1: 5.314 ops/ms
Iteration   1: 7.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.994 ops/ms


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.076 ms/op
Iteration   1: 2.099 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.099 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.056 ms/op
Iteration   1: 1.783 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.783 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.063 ms/op
Iteration   1: 2.163 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.163 ms/op


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.102 ms/op
Iteration   1: 3.657 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.657 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.104 ms/op
Iteration   1: 2.358 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.345 ms/op
                 createUser·p0.99:   9.295 ms/op
                 createUser·p0.999:  20.645 ms/op
                 createUser·p0.9999: 24.055 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13967
  mean =      2.358 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10715 
    [ 2.500,  5.000) = 2950 
    [ 5.000,  7.500) = 135 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.345 ms/op
     p(99.0000) =      9.295 ms/op
     p(99.9000) =     20.645 ms/op
     p(99.9900) =     24.055 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.081 ms/op
Iteration   1: 1.988 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  19.104 ms/op
                 existUser·p0.9999: 19.411 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16088
  mean =      1.988 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 14763 
    [ 2.500,  3.750) = 981 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     19.411 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.096 ms/op
Iteration   1: 2.156 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   1.999 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  18.711 ms/op
                 getUser·p0.9999: 19.154 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14907
  mean =      2.156 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 12981 
    [ 2.500,  3.750) = 1560 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     19.154 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.143 ms/op
Iteration   1: 3.583 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.647 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  19.991 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8933
  mean =      3.583 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 630 
    [ 2.500,  5.000) = 8087 
    [ 5.000,  7.500) = 177 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.647 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     19.991 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.430          ops/ms
ClientSimple.existUser                       thrpt         14.467          ops/ms
ClientSimple.getUser                         thrpt          9.936          ops/ms
ClientSimple.listUser                        thrpt          7.994          ops/ms
ClientSimple.createUser                       avgt          2.099           ms/op
ClientSimple.existUser                        avgt          1.783           ms/op
ClientSimple.getUser                          avgt          2.163           ms/op
ClientSimple.listUser                         avgt          3.657           ms/op
ClientSimple.createUser                     sample  13967   2.358 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.345           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.295           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.645           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.055           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.264           ms/op
ClientSimple.existUser                      sample  16088   1.988 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.710           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.868           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.104           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.411           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.431           ms/op
ClientSimple.getUser                        sample  14907   2.156 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.623           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.999           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.767           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.711           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.154           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.235           ms/op
ClientSimple.listUser                       sample   8933   3.583 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.360           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.647           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.972           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.991           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.889           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.889           ms/op

Benchmark result is saved to 1721176970136.json
