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
# Warmup Iteration   1: 1.591 ops/ms
Iteration   1: 6.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.124 ops/ms


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
# Warmup Iteration   1: 5.314 ops/ms
Iteration   1: 11.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.706 ops/ms


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
# Warmup Iteration   1: 5.062 ops/ms
Iteration   1: 11.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.599 ops/ms


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
# Warmup Iteration   1: 3.883 ops/ms
Iteration   1: 7.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.410 ops/ms


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.072 ms/op
Iteration   1: 2.656 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.656 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.054 ms/op
Iteration   1: 2.095 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.095 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.067 ms/op
Iteration   1: 2.192 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.192 ms/op


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.117 ms/op
Iteration   1: 3.939 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.939 ms/op


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.094 ms/op
Iteration   1: 2.398 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.200 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   10.183 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 18.126 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13845
  mean =      2.398 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 9641 
    [ 2.500,  3.750) = 3305 
    [ 3.750,  5.000) = 379 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.200 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =     10.183 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     18.126 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.105 ms/op
Iteration   1: 2.175 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   2.058 ms/op
                 existUser·p0.90:   2.703 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   4.892 ms/op
                 existUser·p0.999:  27.754 ms/op
                 existUser·p0.9999: 29.820 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14781
  mean =      2.175 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11775 
    [ 2.500,  5.000) = 2898 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      4.892 ms/op
     p(99.9000) =     27.754 ms/op
     p(99.9900) =     29.820 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.162 ms/op
Iteration   1: 2.149 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   2.068 ms/op
                 getUser·p0.90:   2.802 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  13.753 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14919
  mean =      2.149 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 429 
    [ 1.250,  2.500) = 11452 
    [ 2.500,  3.750) = 2777 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     13.753 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 5.786 ±(99.9%) 0.282 ms/op
Iteration   1: 3.407 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  21.746 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9368
  mean =      3.407 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 8566 
    [ 5.000,  7.500) = 338 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     21.746 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.124          ops/ms
ClientSimple.existUser                       thrpt         11.706          ops/ms
ClientSimple.getUser                         thrpt         11.599          ops/ms
ClientSimple.listUser                        thrpt          7.410          ops/ms
ClientSimple.createUser                       avgt          2.656           ms/op
ClientSimple.existUser                        avgt          2.095           ms/op
ClientSimple.getUser                          avgt          2.192           ms/op
ClientSimple.listUser                         avgt          3.939           ms/op
ClientSimple.createUser                     sample  13845   2.398 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.200           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.183           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.334           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.126           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.252           ms/op
ClientSimple.existUser                      sample  14781   2.175 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.398           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.058           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.019           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.892           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.754           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.820           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.852           ms/op
ClientSimple.getUser                        sample  14919   2.149 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.372           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.068           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.472           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.753           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.025           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.041           ms/op
ClientSimple.listUser                       sample   9368   3.407 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.952           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.068           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.635           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.746           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.691           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.691           ms/op

Benchmark result is saved to 1718086373170.json
