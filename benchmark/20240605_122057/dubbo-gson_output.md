# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.041 ops/ms
Iteration   1: 1.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.920 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.383 ops/ms
Iteration   1: 6.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  6.485 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.506 ops/ms
Iteration   1: 3.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  3.913 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.365 ops/ms
Iteration   1: 2.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.692 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 11.708 ±(99.9%) 0.225 ms/op
Iteration   1: 7.345 ±(99.9%) 0.062 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.922 ±(99.9%) 0.095 ms/op
Iteration   1: 3.639 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  3.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.712 ±(99.9%) 0.202 ms/op
Iteration   1: 6.639 ±(99.9%) 0.061 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  6.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.350 ±(99.9%) 0.251 ms/op
Iteration   1: 9.827 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.476 ±(99.9%) 0.330 ms/op
Iteration   1: 7.702 ±(99.9%) 0.153 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   6.980 ms/op
                 createUser·p0.90:   10.404 ms/op
                 createUser·p0.95:   13.050 ms/op
                 createUser·p0.99:   20.827 ms/op
                 createUser·p0.999:  24.402 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 4146
  mean =      7.702 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 152 
    [ 5.000,  7.500) = 2640 
    [ 7.500, 10.000) = 905 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      6.980 ms/op
     p(90.0000) =     10.404 ms/op
     p(95.0000) =     13.050 ms/op
     p(99.0000) =     20.827 ms/op
     p(99.9000) =     24.402 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.137 ms/op
Iteration   1: 3.434 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   12.239 ms/op
                 existUser·p0.999:  18.022 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 9306
  mean =      3.434 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1202 
    [ 2.500,  3.750) = 5964 
    [ 3.750,  5.000) = 1768 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.991 ±(99.9%) 0.334 ms/op
Iteration   1: 6.833 ±(99.9%) 0.085 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   6.709 ms/op
                 getUser·p0.90:   8.733 ms/op
                 getUser·p0.95:   9.819 ms/op
                 getUser·p0.99:   12.051 ms/op
                 getUser·p0.999:  18.659 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 4673
  mean =      6.833 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 12 
    [ 2.500,  3.750) = 47 
    [ 3.750,  5.000) = 478 
    [ 5.000,  6.250) = 1200 
    [ 6.250,  7.500) = 1635 
    [ 7.500,  8.750) = 845 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      6.709 ms/op
     p(90.0000) =      8.733 ms/op
     p(95.0000) =      9.819 ms/op
     p(99.0000) =     12.051 ms/op
     p(99.9000) =     18.659 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.502 ±(99.9%) 0.393 ms/op
Iteration   1: 9.365 ±(99.9%) 0.209 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   8.389 ms/op
                 listUser·p0.90:   13.435 ms/op
                 listUser·p0.95:   14.991 ms/op
                 listUser·p0.99:   23.560 ms/op
                 listUser·p0.999:  32.374 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 3403
  mean =      9.365 ±(99.9%) 0.209 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 99 
    [ 5.000,  7.500) = 1000 
    [ 7.500, 10.000) = 1214 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.724 ms/op
     p(50.0000) =      8.389 ms/op
     p(90.0000) =     13.435 ms/op
     p(95.0000) =     14.991 ms/op
     p(99.0000) =     23.560 ms/op
     p(99.9000) =     32.374 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode   Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt         1.920          ops/ms
ClientSimple.existUser                       thrpt         6.485          ops/ms
ClientSimple.getUser                         thrpt         3.913          ops/ms
ClientSimple.listUser                        thrpt         2.692          ops/ms
ClientSimple.createUser                       avgt         7.345           ms/op
ClientSimple.existUser                        avgt         3.639           ms/op
ClientSimple.getUser                          avgt         6.639           ms/op
ClientSimple.listUser                         avgt         9.827           ms/op
ClientSimple.createUser                     sample  4146   7.702 ± 0.153   ms/op
ClientSimple.createUser:createUser·p0.00    sample         2.187           ms/op
ClientSimple.createUser:createUser·p0.50    sample         6.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample        10.404           ms/op
ClientSimple.createUser:createUser·p0.95    sample        13.050           ms/op
ClientSimple.createUser:createUser·p0.99    sample        20.827           ms/op
ClientSimple.createUser:createUser·p0.999   sample        24.402           ms/op
ClientSimple.createUser:createUser·p0.9999  sample        26.018           ms/op
ClientSimple.createUser:createUser·p1.00    sample        26.018           ms/op
ClientSimple.existUser                      sample  9306   3.434 ± 0.051   ms/op
ClientSimple.existUser:existUser·p0.00      sample         1.335           ms/op
ClientSimple.existUser:existUser·p0.50      sample         3.215           ms/op
ClientSimple.existUser:existUser·p0.90      sample         4.235           ms/op
ClientSimple.existUser:existUser·p0.95      sample         4.743           ms/op
ClientSimple.existUser:existUser·p0.99      sample        12.239           ms/op
ClientSimple.existUser:existUser·p0.999     sample        18.022           ms/op
ClientSimple.existUser:existUser·p0.9999    sample        18.874           ms/op
ClientSimple.existUser:existUser·p1.00      sample        18.874           ms/op
ClientSimple.getUser                        sample  4673   6.833 ± 0.085   ms/op
ClientSimple.getUser:getUser·p0.00          sample         1.255           ms/op
ClientSimple.getUser:getUser·p0.50          sample         6.709           ms/op
ClientSimple.getUser:getUser·p0.90          sample         8.733           ms/op
ClientSimple.getUser:getUser·p0.95          sample         9.819           ms/op
ClientSimple.getUser:getUser·p0.99          sample        12.051           ms/op
ClientSimple.getUser:getUser·p0.999         sample        18.659           ms/op
ClientSimple.getUser:getUser·p0.9999        sample        19.956           ms/op
ClientSimple.getUser:getUser·p1.00          sample        19.956           ms/op
ClientSimple.listUser                       sample  3403   9.365 ± 0.209   ms/op
ClientSimple.listUser:listUser·p0.00        sample         2.724           ms/op
ClientSimple.listUser:listUser·p0.50        sample         8.389           ms/op
ClientSimple.listUser:listUser·p0.90        sample        13.435           ms/op
ClientSimple.listUser:listUser·p0.95        sample        14.991           ms/op
ClientSimple.listUser:listUser·p0.99        sample        23.560           ms/op
ClientSimple.listUser:listUser·p0.999       sample        32.374           ms/op
ClientSimple.listUser:listUser·p0.9999      sample        33.260           ms/op
ClientSimple.listUser:listUser·p1.00        sample        33.260           ms/op

Benchmark result is saved to 1717589800405.json
