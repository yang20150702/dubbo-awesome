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
# Warmup Iteration   1: 2.294 ops/ms
Iteration   1: 7.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.263 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.366 ops/ms
Iteration   1: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.742 ops/ms


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
# Warmup Iteration   1: 6.184 ops/ms
Iteration   1: 12.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.875 ops/ms


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
# Warmup Iteration   1: 5.024 ops/ms
Iteration   1: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.736 ops/ms


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.071 ms/op
Iteration   1: 2.137 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.137 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.048 ms/op
Iteration   1: 1.989 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.989 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.058 ms/op
Iteration   1: 2.098 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.098 ms/op


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.092 ms/op
Iteration   1: 3.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.372 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.090 ms/op
Iteration   1: 2.166 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  23.626 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14791
  mean =      2.166 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12941 
    [ 2.500,  5.000) = 1699 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.072 ms/op
Iteration   1: 2.088 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.048 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.602 ms/op
                 existUser·p0.99:   3.608 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15315
  mean =      2.088 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 13841 
    [ 2.500,  3.750) = 1153 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.602 ms/op
     p(99.0000) =      3.608 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.080 ms/op
Iteration   1: 2.419 ±(99.9%) 0.092 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.703 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   5.733 ms/op
                 getUser·p0.999:  54.401 ms/op
                 getUser·p0.9999: 57.464 ms/op
                 getUser·p1.00:   57.737 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13205
  mean =      2.419 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13033 
    [ 5.000, 10.000) = 64 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 30 
    [45.000, 50.000) = 9 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      5.733 ms/op
     p(99.9000) =     54.401 ms/op
     p(99.9900) =     57.464 ms/op
     p(99.9990) =     57.737 ms/op
     p(99.9999) =     57.737 ms/op
    p(100.0000) =     57.737 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.135 ms/op
Iteration   1: 3.606 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.134 ms/op
                 listUser·p0.999:  19.993 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8854
  mean =      3.606 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1039 
    [ 2.500,  5.000) = 7545 
    [ 5.000,  7.500) = 233 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.134 ms/op
     p(99.9000) =     19.993 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.263          ops/ms
ClientSimple.existUser                       thrpt         12.742          ops/ms
ClientSimple.getUser                         thrpt         12.875          ops/ms
ClientSimple.listUser                        thrpt          8.736          ops/ms
ClientSimple.createUser                       avgt          2.137           ms/op
ClientSimple.existUser                        avgt          1.989           ms/op
ClientSimple.getUser                          avgt          2.098           ms/op
ClientSimple.listUser                         avgt          3.372           ms/op
ClientSimple.createUser                     sample  14791   2.166 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.743           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.104           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.626           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.855           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.855           ms/op
ClientSimple.existUser                      sample  15315   2.088 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.523           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.602           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.608           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.533           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.533           ms/op
ClientSimple.getUser                        sample  13205   2.419 ± 0.092   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.663           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.733           ms/op
ClientSimple.getUser:getUser·p0.999         sample         54.401           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         57.464           ms/op
ClientSimple.getUser:getUser·p1.00          sample         57.737           ms/op
ClientSimple.listUser                       sample   8854   3.606 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.909           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.134           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.993           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.775           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.775           ms/op

Benchmark result is saved to 1720332774694.json
