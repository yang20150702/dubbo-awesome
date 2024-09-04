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
# Warmup Iteration   1: 1.323 ops/ms
Iteration   1: 7.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.327 ops/ms


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
# Warmup Iteration   1: 6.415 ops/ms
Iteration   1: 14.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.329 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.765 ops/ms
Iteration   1: 13.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.428 ops/ms


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
# Warmup Iteration   1: 4.968 ops/ms
Iteration   1: 8.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.812 ops/ms


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.071 ms/op
Iteration   1: 2.156 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.156 ms/op


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
# Warmup Iteration   1: 2.923 ±(99.9%) 0.052 ms/op
Iteration   1: 1.830 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.830 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.045 ms/op
Iteration   1: 2.079 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.079 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.084 ms/op
Iteration   1: 3.594 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.594 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.075 ms/op
Iteration   1: 1.949 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.438 ms/op
                 createUser·p0.50:   1.735 ms/op
                 createUser·p0.90:   2.363 ms/op
                 createUser·p0.95:   2.683 ms/op
                 createUser·p0.99:   7.024 ms/op
                 createUser·p0.999:  27.460 ms/op
                 createUser·p0.9999: 30.409 ms/op
                 createUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16653
  mean =      1.949 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15411 
    [ 2.500,  5.000) = 970 
    [ 5.000,  7.500) = 121 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      7.024 ms/op
     p(99.9000) =     27.460 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 3.030 ±(99.9%) 0.068 ms/op
Iteration   1: 2.190 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.419 ms/op
                 existUser·p0.50:   2.130 ms/op
                 existUser·p0.90:   2.789 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  14.696 ms/op
                 existUser·p0.9999: 15.185 ms/op
                 existUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14664
  mean =      2.190 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 328 
    [ 1.250,  2.500) = 11387 
    [ 2.500,  3.750) = 2777 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     15.185 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.115 ms/op
Iteration   1: 2.000 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 20.559 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15986
  mean =      2.000 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14830 
    [ 2.500,  5.000) = 1030 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     20.559 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.141 ms/op
Iteration   1: 3.095 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   2.761 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  18.902 ms/op
                 listUser·p0.9999: 19.921 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10169
  mean =      3.095 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1530 
    [ 2.500,  3.750) = 7013 
    [ 3.750,  5.000) = 1385 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     18.902 ms/op
     p(99.9900) =     19.921 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.327          ops/ms
ClientSimple.existUser                       thrpt         14.329          ops/ms
ClientSimple.getUser                         thrpt         13.428          ops/ms
ClientSimple.listUser                        thrpt          8.812          ops/ms
ClientSimple.createUser                       avgt          2.156           ms/op
ClientSimple.existUser                        avgt          1.830           ms/op
ClientSimple.getUser                          avgt          2.079           ms/op
ClientSimple.listUser                         avgt          3.594           ms/op
ClientSimple.createUser                     sample  16653   1.949 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.438           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.735           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.024           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.460           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.409           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.540           ms/op
ClientSimple.existUser                      sample  14664   2.190 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.419           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.998           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.399           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.696           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.185           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.254           ms/op
ClientSimple.getUser                        sample  15986   2.000 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.617           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.858           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.890           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.559           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.578           ms/op
ClientSimple.listUser                       sample  10169   3.095 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.761           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.750           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.902           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.921           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.923           ms/op

Benchmark result is saved to 1725452345829.json
