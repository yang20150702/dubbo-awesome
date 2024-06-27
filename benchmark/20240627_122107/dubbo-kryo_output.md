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
# Warmup Iteration   1: 1.632 ops/ms
Iteration   1: 6.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.921 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.876 ops/ms
Iteration   1: 11.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.909 ops/ms


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
# Warmup Iteration   1: 4.865 ops/ms
Iteration   1: 9.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.645 ops/ms


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
# Warmup Iteration   1: 4.339 ops/ms
Iteration   1: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.921 ops/ms


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.107 ms/op
Iteration   1: 2.551 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.551 ms/op


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
# Warmup Iteration   1: 5.103 ±(99.9%) 0.113 ms/op
Iteration   1: 2.578 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.578 ms/op


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
# Warmup Iteration   1: 5.509 ±(99.9%) 0.115 ms/op
Iteration   1: 2.438 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.438 ms/op


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
# Warmup Iteration   1: 4.999 ±(99.9%) 0.113 ms/op
Iteration   1: 3.737 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.737 ms/op


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.147 ms/op
Iteration   1: 2.513 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.889 ms/op
                 createUser·p0.99:   11.448 ms/op
                 createUser·p0.999:  14.755 ms/op
                 createUser·p0.9999: 15.906 ms/op
                 createUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12708
  mean =      2.513 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 8989 
    [ 2.500,  3.750) = 2984 
    [ 3.750,  5.000) = 244 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.889 ms/op
     p(99.0000) =     11.448 ms/op
     p(99.9000) =     14.755 ms/op
     p(99.9900) =     15.906 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.084 ms/op
Iteration   1: 2.149 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   5.875 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15023
  mean =      2.149 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 11676 
    [ 2.500,  3.750) = 2927 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      5.875 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.087 ms/op
Iteration   1: 2.601 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.195 ms/op
                 getUser·p0.95:   3.514 ms/op
                 getUser·p0.99:   5.511 ms/op
                 getUser·p0.999:  18.482 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12327
  mean =      2.601 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 6507 
    [ 2.500,  3.750) = 5403 
    [ 3.750,  5.000) = 194 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      5.511 ms/op
     p(99.9000) =     18.482 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.136 ms/op
Iteration   1: 3.360 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.959 ms/op
                 listUser·p0.999:  24.821 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9522
  mean =      3.360 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1216 
    [ 2.500,  5.000) = 8007 
    [ 5.000,  7.500) = 256 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.959 ms/op
     p(99.9000) =     24.821 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.921          ops/ms
ClientSimple.existUser                       thrpt         11.909          ops/ms
ClientSimple.getUser                         thrpt          9.645          ops/ms
ClientSimple.listUser                        thrpt          7.921          ops/ms
ClientSimple.createUser                       avgt          2.551           ms/op
ClientSimple.existUser                        avgt          2.578           ms/op
ClientSimple.getUser                          avgt          2.438           ms/op
ClientSimple.listUser                         avgt          3.737           ms/op
ClientSimple.createUser                     sample  12708   2.513 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.791           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.889           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.448           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.755           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.906           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.204           ms/op
ClientSimple.existUser                      sample  15023   2.149 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.689           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.879           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.133           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.875           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.153           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.940           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.973           ms/op
ClientSimple.getUser                        sample  12327   2.601 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.618           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.195           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.514           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.511           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.482           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.874           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.874           ms/op
ClientSimple.listUser                       sample   9522   3.360 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.992           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.959           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.821           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.706           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.706           ms/op

Benchmark result is saved to 1719490619718.json
