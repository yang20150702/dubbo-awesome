# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.744 ops/ms
Iteration   1: 6.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.346 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.180 ops/ms
Iteration   1: 14.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.829 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.572 ops/ms
Iteration   1: 11.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.609 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.433 ops/ms
Iteration   1: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.735 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.371 ±(99.9%) 0.098 ms/op
Iteration   1: 2.412 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.412 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ±(99.9%) 0.059 ms/op
Iteration   1: 1.822 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ±(99.9%) 0.052 ms/op
Iteration   1: 2.093 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.089 ms/op
Iteration   1: 3.490 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.280 ±(99.9%) 0.088 ms/op
Iteration   1: 2.725 ±(99.9%) 0.114 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   2.945 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   15.046 ms/op
                 createUser·p0.999:  57.949 ms/op
                 createUser·p0.9999: 58.905 ms/op
                 createUser·p1.00:   58.917 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11763
  mean =      2.725 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11372 
    [ 5.000, 10.000) = 179 
    [10.000, 15.000) = 94 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =     15.046 ms/op
     p(99.9000) =     57.949 ms/op
     p(99.9900) =     58.905 ms/op
     p(99.9990) =     58.917 ms/op
     p(99.9999) =     58.917 ms/op
    p(100.0000) =     58.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.873 ±(99.9%) 0.075 ms/op
Iteration   1: 2.139 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.240 ms/op
                 existUser·p0.50:   2.079 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   3.709 ms/op
                 existUser·p0.999:  10.044 ms/op
                 existUser·p0.9999: 10.265 ms/op
                 existUser·p1.00:   10.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14939
  mean =      2.139 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 11101 
    [ 2.500,  3.750) = 3503 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.240 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.709 ms/op
     p(99.9000) =     10.044 ms/op
     p(99.9900) =     10.265 ms/op
     p(99.9990) =     10.273 ms/op
     p(99.9999) =     10.273 ms/op
    p(100.0000) =     10.273 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ±(99.9%) 0.085 ms/op
Iteration   1: 2.030 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   4.201 ms/op
                 getUser·p0.999:  16.833 ms/op
                 getUser·p0.9999: 17.315 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15761
  mean =      2.030 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 464 
    [ 1.250,  2.500) = 13253 
    [ 2.500,  3.750) = 1869 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.201 ms/op
     p(99.9000) =     16.833 ms/op
     p(99.9900) =     17.315 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.139 ms/op
Iteration   1: 3.639 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  8.507 ms/op
                 listUser·p0.9999: 9.028 ms/op
                 listUser·p1.00:   9.028 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8802
  mean =      3.639 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 78 
    [ 2.000,  3.000) = 1442 
    [ 3.000,  4.000) = 5113 
    [ 4.000,  5.000) = 1780 
    [ 5.000,  6.000) = 189 
    [ 6.000,  7.000) = 158 
    [ 7.000,  8.000) = 23 
    [ 8.000,  9.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =      8.507 ms/op
     p(99.9900) =      9.028 ms/op
     p(99.9990) =      9.028 ms/op
     p(99.9999) =      9.028 ms/op
    p(100.0000) =      9.028 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.346          ops/ms
ClientSimple.existUser                       thrpt         14.829          ops/ms
ClientSimple.getUser                         thrpt         11.609          ops/ms
ClientSimple.listUser                        thrpt          8.735          ops/ms
ClientSimple.createUser                       avgt          2.412           ms/op
ClientSimple.existUser                        avgt          1.822           ms/op
ClientSimple.getUser                          avgt          2.093           ms/op
ClientSimple.listUser                         avgt          3.490           ms/op
ClientSimple.createUser                     sample  11763   2.725 ± 0.114   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.506           ms/op
ClientSimple.createUser:createUser·p0.99    sample         15.046           ms/op
ClientSimple.createUser:createUser·p0.999   sample         57.949           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         58.905           ms/op
ClientSimple.createUser:createUser·p1.00    sample         58.917           ms/op
ClientSimple.existUser                      sample  14939   2.139 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.240           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.079           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.912           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.709           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.044           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.265           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.273           ms/op
ClientSimple.getUser                        sample  15761   2.030 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.583           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.201           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.833           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.315           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.334           ms/op
ClientSimple.listUser                       sample   8802   3.639 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.883           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.644           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.507           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.028           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.028           ms/op

Benchmark result is saved to 1722991413101.json
