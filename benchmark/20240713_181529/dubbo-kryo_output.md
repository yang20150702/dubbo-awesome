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
# Warmup Iteration   1: 1.039 ops/ms
Iteration   1: 6.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.452 ops/ms


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
# Warmup Iteration   1: 6.244 ops/ms
Iteration   1: 12.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.298 ops/ms


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
# Warmup Iteration   1: 5.729 ops/ms
Iteration   1: 13.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.502 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.192 ops/ms
Iteration   1: 8.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.862 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.077 ms/op
Iteration   1: 2.069 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.069 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ±(99.9%) 0.050 ms/op
Iteration   1: 1.938 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.938 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.177 ±(99.9%) 0.062 ms/op
Iteration   1: 1.927 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.927 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.428 ±(99.9%) 0.085 ms/op
Iteration   1: 4.122 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.122 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.509 ±(99.9%) 0.098 ms/op
Iteration   1: 2.076 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.732 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   3.567 ms/op
                 createUser·p0.999:  13.966 ms/op
                 createUser·p0.9999: 15.041 ms/op
                 createUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15601
  mean =      2.076 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 12116 
    [ 2.500,  3.750) = 3083 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      3.567 ms/op
     p(99.9000) =     13.966 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.052 ±(99.9%) 0.078 ms/op
Iteration   1: 1.793 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.651 ms/op
                 existUser·p0.999:  11.146 ms/op
                 existUser·p0.9999: 11.854 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18345
  mean =      1.793 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 240 
    [ 1.250,  2.500) = 17111 
    [ 2.500,  3.750) = 819 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.651 ms/op
     p(99.9000) =     11.146 ms/op
     p(99.9900) =     11.854 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.082 ms/op
Iteration   1: 2.122 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   2.056 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 18.464 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15200
  mean =      2.122 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 429 
    [ 1.250,  2.500) = 11976 
    [ 2.500,  3.750) = 2601 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     18.464 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.151 ms/op
Iteration   1: 3.480 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  6.420 ms/op
                 listUser·p0.9999: 9.273 ms/op
                 listUser·p1.00:   9.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9287
  mean =      3.480 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 32 
    [ 1.500,  2.000) = 64 
    [ 2.000,  2.500) = 310 
    [ 2.500,  3.000) = 2100 
    [ 3.000,  3.500) = 2012 
    [ 3.500,  4.000) = 3035 
    [ 4.000,  4.500) = 1076 
    [ 4.500,  5.000) = 501 
    [ 5.000,  5.500) = 76 
    [ 5.500,  6.000) = 34 
    [ 6.000,  6.500) = 42 
    [ 6.500,  7.000) = 3 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 1 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =      6.420 ms/op
     p(99.9900) =      9.273 ms/op
     p(99.9990) =      9.273 ms/op
     p(99.9999) =      9.273 ms/op
    p(100.0000) =      9.273 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.452          ops/ms
ClientSimple.existUser                       thrpt         12.298          ops/ms
ClientSimple.getUser                         thrpt         13.502          ops/ms
ClientSimple.listUser                        thrpt          8.862          ops/ms
ClientSimple.createUser                       avgt          2.069           ms/op
ClientSimple.existUser                        avgt          1.938           ms/op
ClientSimple.getUser                          avgt          1.927           ms/op
ClientSimple.listUser                         avgt          4.122           ms/op
ClientSimple.createUser                     sample  15601   2.076 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.528           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.567           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.966           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.041           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.253           ms/op
ClientSimple.existUser                      sample  18345   1.793 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.431           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.663           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.651           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.146           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.854           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.059           ms/op
ClientSimple.getUser                        sample  15200   2.122 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.538           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.056           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.170           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.383           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.464           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.481           ms/op
ClientSimple.listUser                       sample   9287   3.480 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.077           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.420           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.273           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.273           ms/op

Benchmark result is saved to 1720894273079.json
