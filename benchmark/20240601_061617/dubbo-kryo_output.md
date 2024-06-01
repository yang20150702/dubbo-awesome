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
# Warmup Iteration   1: 1.298 ops/ms
Iteration   1: 5.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.888 ops/ms


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
# Warmup Iteration   1: 4.840 ops/ms
Iteration   1: 11.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.447 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ops/ms
Iteration   1: 12.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.049 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ops/ms
Iteration   1: 7.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.583 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ±(99.9%) 0.085 ms/op
Iteration   1: 2.228 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.228 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.066 ms/op
Iteration   1: 2.072 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.072 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.065 ms/op
Iteration   1: 2.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.051 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.115 ms/op
Iteration   1: 3.418 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.418 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.100 ms/op
Iteration   1: 2.201 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  28.770 ms/op
                 createUser·p0.9999: 29.224 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14521
  mean =      2.201 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11439 
    [ 2.500,  5.000) = 2971 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =     28.770 ms/op
     p(99.9900) =     29.224 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.078 ms/op
Iteration   1: 1.997 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   1.915 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 13.704 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15980
  mean =      1.997 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 14482 
    [ 2.500,  3.750) = 950 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     13.704 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 3.607 ±(99.9%) 0.088 ms/op
Iteration   1: 2.263 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  26.408 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14135
  mean =      2.263 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11460 
    [ 2.500,  5.000) = 2396 
    [ 5.000,  7.500) = 212 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     26.408 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 5.006 ±(99.9%) 0.153 ms/op
Iteration   1: 3.728 ±(99.9%) 0.212 ms/op
                 listUser·p0.00:   0.638 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.812 ms/op
                 listUser·p0.999:  105.071 ms/op
                 listUser·p0.9999: 120.455 ms/op
                 listUser·p1.00:   120.455 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8566
  mean =      3.728 ±(99.9%) 0.212 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8508 
    [ 12.500,  25.000) = 8 
    [ 25.000,  37.500) = 11 
    [ 37.500,  50.000) = 6 
    [ 50.000,  62.500) = 1 
    [ 62.500,  75.000) = 2 
    [ 75.000,  87.500) = 8 
    [ 87.500, 100.000) = 12 
    [100.000, 112.500) = 4 
    [112.500, 125.000) = 6 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.812 ms/op
     p(99.9000) =    105.071 ms/op
     p(99.9900) =    120.455 ms/op
     p(99.9990) =    120.455 ms/op
     p(99.9999) =    120.455 ms/op
    p(100.0000) =    120.455 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           5.888          ops/ms
ClientSimple.existUser                       thrpt          11.447          ops/ms
ClientSimple.getUser                         thrpt          12.049          ops/ms
ClientSimple.listUser                        thrpt           7.583          ops/ms
ClientSimple.createUser                       avgt           2.228           ms/op
ClientSimple.existUser                        avgt           2.072           ms/op
ClientSimple.getUser                          avgt           2.051           ms/op
ClientSimple.listUser                         avgt           3.418           ms/op
ClientSimple.createUser                     sample  14521    2.201 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.522           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.109           ms/op
ClientSimple.createUser:createUser·p0.99    sample           3.772           ms/op
ClientSimple.createUser:createUser·p0.999   sample          28.770           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          29.224           ms/op
ClientSimple.createUser:createUser·p1.00    sample          29.327           ms/op
ClientSimple.existUser                      sample  15980    1.997 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.365           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.915           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.342           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.813           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          13.704           ms/op
ClientSimple.existUser:existUser·p1.00      sample          13.861           ms/op
ClientSimple.getUser                        sample  14135    2.263 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.867           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.080           ms/op
ClientSimple.getUser:getUser·p0.99          sample           6.595           ms/op
ClientSimple.getUser:getUser·p0.999         sample          26.408           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientSimple.getUser:getUser·p1.00          sample          26.804           ms/op
ClientSimple.listUser                       sample   8566    3.728 ± 0.212   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.638           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample           7.812           ms/op
ClientSimple.listUser:listUser·p0.999       sample         105.071           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         120.455           ms/op
ClientSimple.listUser:listUser·p1.00        sample         120.455           ms/op

Benchmark result is saved to 1717222318356.json
