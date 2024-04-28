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
# Warmup Iteration   1: 1.539 ops/ms
Iteration   1: 6.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.135 ops/ms


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
# Warmup Iteration   1: 5.377 ops/ms
Iteration   1: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.851 ops/ms


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
# Warmup Iteration   1: 4.505 ops/ms
Iteration   1: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.626 ops/ms


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
# Warmup Iteration   1: 4.989 ops/ms
Iteration   1: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.984 ops/ms


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.090 ms/op
Iteration   1: 2.234 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.234 ms/op


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
# Warmup Iteration   1: 3.430 ±(99.9%) 0.055 ms/op
Iteration   1: 1.905 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.064 ms/op
Iteration   1: 2.000 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.000 ms/op


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.135 ms/op
Iteration   1: 3.813 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.813 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.100 ms/op
Iteration   1: 2.358 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   2.884 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   5.871 ms/op
                 createUser·p0.999:  16.105 ms/op
                 createUser·p0.9999: 17.519 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13565
  mean =      2.358 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 271 
    [ 1.250,  2.500) = 9166 
    [ 2.500,  3.750) = 3870 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      5.871 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     17.519 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 2.954 ±(99.9%) 0.064 ms/op
Iteration   1: 1.843 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.371 ms/op
                 existUser·p0.50:   1.755 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  19.562 ms/op
                 existUser·p0.9999: 20.227 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17338
  mean =      1.843 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16769 
    [ 2.500,  5.000) = 470 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     20.227 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.084 ms/op
Iteration   1: 2.376 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.269 ms/op
                 getUser·p0.90:   2.997 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  11.223 ms/op
                 getUser·p0.9999: 11.305 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13482
  mean =      2.376 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 8508 
    [ 2.500,  3.750) = 4695 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.997 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     11.223 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.375 ±(99.9%) 0.158 ms/op
Iteration   1: 3.529 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.358 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8997
  mean =      3.529 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 908 
    [ 2.500,  5.000) = 7748 
    [ 5.000,  7.500) = 255 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.358 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.135          ops/ms
ClientSimple.existUser                       thrpt         10.851          ops/ms
ClientSimple.getUser                         thrpt         12.626          ops/ms
ClientSimple.listUser                        thrpt          7.984          ops/ms
ClientSimple.createUser                       avgt          2.234           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          2.000           ms/op
ClientSimple.listUser                         avgt          3.813           ms/op
ClientSimple.createUser                     sample  13565   2.358 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.659           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.871           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.105           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.519           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.531           ms/op
ClientSimple.existUser                      sample  17338   1.843 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.371           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.755           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.562           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.227           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.251           ms/op
ClientSimple.getUser                        sample  13482   2.376 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.883           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.997           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.269           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.423           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.223           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.305           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.305           ms/op
ClientSimple.listUser                       sample   8997   3.529 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.925           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.358           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.268           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.496           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.496           ms/op

Benchmark result is saved to 1714327797781.json
