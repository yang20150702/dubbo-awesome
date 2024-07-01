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
# Warmup Iteration   1: 1.296 ops/ms
Iteration   1: 5.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.797 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ops/ms
Iteration   1: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.098 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.677 ops/ms
Iteration   1: 10.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.689 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.324 ops/ms
Iteration   1: 7.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.055 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.711 ±(99.9%) 0.094 ms/op
Iteration   1: 2.535 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.535 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.396 ±(99.9%) 0.068 ms/op
Iteration   1: 2.325 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.325 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.135 ms/op
Iteration   1: 2.762 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.762 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ±(99.9%) 0.136 ms/op
Iteration   1: 4.016 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.016 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.110 ms/op
Iteration   1: 2.719 ±(99.9%) 0.063 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   2.376 ms/op
                 createUser·p0.90:   3.153 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   12.605 ms/op
                 createUser·p0.999:  28.907 ms/op
                 createUser·p0.9999: 31.653 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11841
  mean =      2.719 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7179 
    [ 2.500,  5.000) = 4159 
    [ 5.000,  7.500) = 221 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.376 ms/op
     p(90.0000) =      3.153 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =     12.605 ms/op
     p(99.9000) =     28.907 ms/op
     p(99.9900) =     31.653 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.095 ms/op
Iteration   1: 2.213 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.105 ms/op
                 existUser·p0.90:   2.695 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  16.756 ms/op
                 existUser·p0.9999: 17.061 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14479
  mean =      2.213 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 11705 
    [ 2.500,  3.750) = 2447 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     16.756 ms/op
     p(99.9900) =     17.061 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.104 ms/op
Iteration   1: 2.496 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.286 ms/op
                 getUser·p0.90:   3.046 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12793
  mean =      2.496 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 8240 
    [ 2.500,  3.750) = 4122 
    [ 3.750,  5.000) = 281 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      3.046 ms/op
     p(95.0000) =      3.342 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 6.039 ±(99.9%) 0.290 ms/op
Iteration   1: 4.424 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   9.209 ms/op
                 listUser·p0.999:  20.021 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7214
  mean =      4.424 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 5852 
    [ 5.000,  7.500) = 1148 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      9.209 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.797          ops/ms
ClientSimple.existUser                       thrpt         10.098          ops/ms
ClientSimple.getUser                         thrpt         10.689          ops/ms
ClientSimple.listUser                        thrpt          7.055          ops/ms
ClientSimple.createUser                       avgt          2.535           ms/op
ClientSimple.existUser                        avgt          2.325           ms/op
ClientSimple.getUser                          avgt          2.762           ms/op
ClientSimple.listUser                         avgt          4.016           ms/op
ClientSimple.createUser                     sample  11841   2.719 ± 0.063   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.524           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.376           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.153           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.448           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.605           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.907           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.653           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.719           ms/op
ClientSimple.existUser                      sample  14479   2.213 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.905           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.105           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.317           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.756           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.061           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.105           ms/op
ClientSimple.getUser                        sample  12793   2.496 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.005           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.286           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.046           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.342           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.710           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.302           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.662           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.662           ms/op
ClientSimple.listUser                       sample   7214   4.424 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          2.134           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.472           ms/op
ClientSimple.listUser:listUser·p0.95        sample          6.201           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.209           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.021           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.775           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.775           ms/op

Benchmark result is saved to 1719814476746.json
