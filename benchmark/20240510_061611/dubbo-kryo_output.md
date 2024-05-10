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
# Warmup Iteration   1: 2.012 ops/ms
Iteration   1: 7.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.447 ops/ms


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
# Warmup Iteration   1: 7.347 ops/ms
Iteration   1: 12.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.877 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ops/ms
Iteration   1: 14.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.051 ops/ms


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
# Warmup Iteration   1: 5.279 ops/ms
Iteration   1: 8.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.797 ops/ms


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.053 ms/op
Iteration   1: 2.317 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.317 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.048 ms/op
Iteration   1: 1.732 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.732 ms/op


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.059 ms/op
Iteration   1: 2.152 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.152 ms/op


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
# Warmup Iteration   1: 5.451 ±(99.9%) 0.102 ms/op
Iteration   1: 3.661 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.661 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.099 ms/op
Iteration   1: 2.235 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.433 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14440
  mean =      2.235 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 12592 
    [ 2.500,  3.750) = 1147 
    [ 3.750,  5.000) = 182 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 2.869 ±(99.9%) 0.066 ms/op
Iteration   1: 1.817 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.023 ms/op
                 existUser·p0.95:   2.191 ms/op
                 existUser·p0.99:   3.232 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 11.305 ms/op
                 existUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17590
  mean =      1.817 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 17066 
    [ 2.500,  3.750) = 293 
    [ 3.750,  5.000) = 1 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.023 ms/op
     p(95.0000) =      2.191 ms/op
     p(99.0000) =      3.232 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     11.305 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.079 ms/op
Iteration   1: 2.436 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.206 ms/op
                 getUser·p0.50:   2.327 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.453 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  27.283 ms/op
                 getUser·p0.9999: 28.336 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13125
  mean =      2.436 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7295 
    [ 2.500,  5.000) = 5649 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.206 ms/op
     p(50.0000) =      2.327 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     27.283 ms/op
     p(99.9900) =     28.336 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.123 ms/op
Iteration   1: 3.038 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   2.785 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.079 ms/op
                 listUser·p0.999:  6.418 ms/op
                 listUser·p0.9999: 7.735 ms/op
                 listUser·p1.00:   7.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10519
  mean =      3.038 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 98 
    [2.000, 2.500) = 1542 
    [2.500, 3.000) = 5220 
    [3.000, 3.500) = 985 
    [3.500, 4.000) = 1640 
    [4.000, 4.500) = 649 
    [4.500, 5.000) = 236 
    [5.000, 5.500) = 76 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      6.418 ms/op
     p(99.9900) =      7.735 ms/op
     p(99.9990) =      7.791 ms/op
     p(99.9999) =      7.791 ms/op
    p(100.0000) =      7.791 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.447          ops/ms
ClientSimple.existUser                       thrpt         12.877          ops/ms
ClientSimple.getUser                         thrpt         14.051          ops/ms
ClientSimple.listUser                        thrpt          8.797          ops/ms
ClientSimple.createUser                       avgt          2.317           ms/op
ClientSimple.existUser                        avgt          1.732           ms/op
ClientSimple.getUser                          avgt          2.152           ms/op
ClientSimple.listUser                         avgt          3.661           ms/op
ClientSimple.createUser                     sample  14440   2.235 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.433           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.239           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.890           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.988           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  17590   1.817 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.595           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.232           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.600           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.305           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.305           ms/op
ClientSimple.getUser                        sample  13125   2.436 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.206           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.154           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.453           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.513           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.283           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.336           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.541           ms/op
ClientSimple.listUser                       sample  10519   3.038 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.176           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.785           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.985           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.418           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.735           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.791           ms/op

Benchmark result is saved to 1715321511179.json
