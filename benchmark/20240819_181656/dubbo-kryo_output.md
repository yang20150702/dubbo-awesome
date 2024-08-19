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
# Warmup Iteration   1: 1.869 ops/ms
Iteration   1: 6.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.380 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.029 ops/ms
Iteration   1: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.825 ops/ms


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
# Warmup Iteration   1: 6.379 ops/ms
Iteration   1: 13.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.372 ops/ms


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
# Warmup Iteration   1: 4.234 ops/ms
Iteration   1: 8.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.892 ops/ms


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
# Warmup Iteration   1: 3.524 ±(99.9%) 0.060 ms/op
Iteration   1: 2.204 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.204 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.060 ±(99.9%) 0.060 ms/op
Iteration   1: 1.875 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ±(99.9%) 0.051 ms/op
Iteration   1: 1.926 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.926 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.898 ±(99.9%) 0.094 ms/op
Iteration   1: 3.182 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.182 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.102 ms/op
Iteration   1: 2.063 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.634 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   5.977 ms/op
                 createUser·p0.999:  16.278 ms/op
                 createUser·p0.9999: 17.335 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15490
  mean =      2.063 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 617 
    [ 1.250,  2.500) = 12570 
    [ 2.500,  3.750) = 2028 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      5.977 ms/op
     p(99.9000) =     16.278 ms/op
     p(99.9900) =     17.335 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 2.896 ±(99.9%) 0.072 ms/op
Iteration   1: 1.867 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.453 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   3.349 ms/op
                 existUser·p0.999:  23.167 ms/op
                 existUser·p0.9999: 24.600 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17130
  mean =      1.867 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16655 
    [ 2.500,  5.000) = 362 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      3.349 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     24.600 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.076 ms/op
Iteration   1: 2.016 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.464 ms/op
                 getUser·p0.50:   1.915 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.328 ms/op
                 getUser·p0.999:  15.024 ms/op
                 getUser·p0.9999: 15.278 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15854
  mean =      2.016 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 289 
    [ 1.250,  2.500) = 13427 
    [ 2.500,  3.750) = 2053 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.328 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     15.278 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.131 ms/op
Iteration   1: 3.877 ±(99.9%) 0.073 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  32.555 ms/op
                 listUser·p0.9999: 32.866 ms/op
                 listUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8248
  mean =      3.877 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 7620 
    [ 5.000,  7.500) = 326 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     32.555 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.380          ops/ms
ClientSimple.existUser                       thrpt         12.825          ops/ms
ClientSimple.getUser                         thrpt         13.372          ops/ms
ClientSimple.listUser                        thrpt          8.892          ops/ms
ClientSimple.createUser                       avgt          2.204           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          1.926           ms/op
ClientSimple.listUser                         avgt          3.182           ms/op
ClientSimple.createUser                     sample  15490   2.063 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.635           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.977           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.278           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.335           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.695           ms/op
ClientSimple.existUser                      sample  17130   1.867 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.453           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.163           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.349           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.167           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.600           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.740           ms/op
ClientSimple.getUser                        sample  15854   2.016 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.464           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.915           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.328           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.024           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.278           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.335           ms/op
ClientSimple.listUser                       sample   8248   3.877 ± 0.073   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.354           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.930           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.555           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.866           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.866           ms/op

Benchmark result is saved to 1724091172284.json
