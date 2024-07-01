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
# Warmup Iteration   1: 1.867 ops/ms
Iteration   1: 7.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.133 ops/ms


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
# Warmup Iteration   1: 5.903 ops/ms
Iteration   1: 12.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.347 ops/ms


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
# Warmup Iteration   1: 5.611 ops/ms
Iteration   1: 11.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.980 ops/ms


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
# Warmup Iteration   1: 5.227 ops/ms
Iteration   1: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.294 ops/ms


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.096 ms/op
Iteration   1: 2.441 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.441 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.045 ms/op
Iteration   1: 1.773 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.773 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.047 ms/op
Iteration   1: 2.087 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.087 ms/op


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.098 ms/op
Iteration   1: 3.414 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.414 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.076 ms/op
Iteration   1: 2.205 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.240 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.827 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  31.016 ms/op
                 createUser·p0.9999: 33.758 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14495
  mean =      2.205 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12145 
    [ 2.500,  5.000) = 2194 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.240 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.827 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     31.016 ms/op
     p(99.9900) =     33.758 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 2.901 ±(99.9%) 0.059 ms/op
Iteration   1: 1.764 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.401 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   2.075 ms/op
                 existUser·p0.95:   2.249 ms/op
                 existUser·p0.99:   4.365 ms/op
                 existUser·p0.999:  35.586 ms/op
                 existUser·p0.9999: 35.914 ms/op
                 existUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18119
  mean =      1.764 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17686 
    [ 2.500,  5.000) = 293 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      2.075 ms/op
     p(95.0000) =      2.249 ms/op
     p(99.0000) =      4.365 ms/op
     p(99.9000) =     35.586 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 3.384 ±(99.9%) 0.092 ms/op
Iteration   1: 1.909 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   1.737 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.392 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 18.895 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16742
  mean =      1.909 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 184 
    [ 1.250,  2.500) = 15436 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.392 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     18.895 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.179 ms/op
Iteration   1: 3.318 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.518 ms/op
                 listUser·p0.50:   3.383 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.210 ms/op
                 listUser·p0.999:  7.414 ms/op
                 listUser·p0.9999: 8.897 ms/op
                 listUser·p1.00:   8.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9636
  mean =      3.318 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 19 
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 109 
    [2.000, 2.500) = 1478 
    [2.500, 3.000) = 1836 
    [3.000, 3.500) = 2111 
    [3.500, 4.000) = 2922 
    [4.000, 4.500) = 600 
    [4.500, 5.000) = 195 
    [5.000, 5.500) = 138 
    [5.500, 6.000) = 67 
    [6.000, 6.500) = 89 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 35 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =      8.897 ms/op
     p(99.9990) =      8.897 ms/op
     p(99.9999) =      8.897 ms/op
    p(100.0000) =      8.897 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.133          ops/ms
ClientSimple.existUser                       thrpt         12.347          ops/ms
ClientSimple.getUser                         thrpt         11.980          ops/ms
ClientSimple.listUser                        thrpt          8.294          ops/ms
ClientSimple.createUser                       avgt          2.441           ms/op
ClientSimple.existUser                        avgt          1.773           ms/op
ClientSimple.getUser                          avgt          2.087           ms/op
ClientSimple.listUser                         avgt          3.414           ms/op
ClientSimple.createUser                     sample  14495   2.205 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.240           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.827           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.341           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.016           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.758           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.817           ms/op
ClientSimple.existUser                      sample  18119   1.764 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.401           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.589           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.075           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.249           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.365           ms/op
ClientSimple.existUser:existUser·p0.999     sample         35.586           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         35.914           ms/op
ClientSimple.existUser:existUser·p1.00      sample         35.914           ms/op
ClientSimple.getUser                        sample  16742   1.909 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.534           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.737           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.392           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.547           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.895           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.005           ms/op
ClientSimple.listUser                       sample   9636   3.318 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.518           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.383           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.210           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.414           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.897           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.897           ms/op

Benchmark result is saved to 1719836287185.json
