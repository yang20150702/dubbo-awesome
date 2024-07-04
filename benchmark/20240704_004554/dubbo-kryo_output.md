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
# Warmup Iteration   1: 1.660 ops/ms
Iteration   1: 6.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.899 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.510 ops/ms
Iteration   1: 9.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.475 ops/ms


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
# Warmup Iteration   1: 5.568 ops/ms
Iteration   1: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.469 ops/ms


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
# Warmup Iteration   1: 3.921 ops/ms
Iteration   1: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.195 ops/ms


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.084 ms/op
Iteration   1: 2.215 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.053 ms/op
Iteration   1: 2.032 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.032 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.112 ms/op
Iteration   1: 1.981 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.981 ms/op


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
# Warmup Iteration   1: 5.489 ±(99.9%) 0.136 ms/op
Iteration   1: 4.021 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.021 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.099 ms/op
Iteration   1: 2.152 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   6.466 ms/op
                 createUser·p0.999:  17.884 ms/op
                 createUser·p0.9999: 18.038 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15223
  mean =      2.152 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 13731 
    [ 2.500,  3.750) = 1013 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      6.466 ms/op
     p(99.9000) =     17.884 ms/op
     p(99.9900) =     18.038 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.069 ms/op
Iteration   1: 1.979 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   5.011 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 14.856 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16429
  mean =      1.979 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 248 
    [ 1.250,  2.500) = 14629 
    [ 2.500,  3.750) = 1338 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 124 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      5.011 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     14.856 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.327 ms/op
Iteration   1: 2.202 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   2.038 ms/op
                 getUser·p0.90:   2.781 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.935 ms/op
                 getUser·p0.999:  18.266 ms/op
                 getUser·p0.9999: 18.968 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14516
  mean =      2.202 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 11421 
    [ 2.500,  3.750) = 2859 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.935 ms/op
     p(99.9000) =     18.266 ms/op
     p(99.9900) =     18.968 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 6.645 ±(99.9%) 0.208 ms/op
Iteration   1: 3.852 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   9.742 ms/op
                 listUser·p0.999:  26.236 ms/op
                 listUser·p0.9999: 27.329 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8339
  mean =      3.852 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 364 
    [ 2.500,  5.000) = 7427 
    [ 5.000,  7.500) = 400 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      9.742 ms/op
     p(99.9000) =     26.236 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.899          ops/ms
ClientSimple.existUser                       thrpt          9.475          ops/ms
ClientSimple.getUser                         thrpt         10.469          ops/ms
ClientSimple.listUser                        thrpt          8.195          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          2.032           ms/op
ClientSimple.getUser                          avgt          1.981           ms/op
ClientSimple.listUser                         avgt          4.021           ms/op
ClientSimple.createUser                     sample  15223   2.152 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.638           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.466           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.884           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.038           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.055           ms/op
ClientSimple.existUser                      sample  16429   1.979 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.553           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.011           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.762           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.856           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.877           ms/op
ClientSimple.getUser                        sample  14516   2.202 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.038           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.052           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.935           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.266           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.968           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.235           ms/op
ClientSimple.listUser                       sample   8339   3.852 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.806           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.637           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.431           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.742           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.329           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.329           ms/op

Benchmark result is saved to 1720053701515.json
