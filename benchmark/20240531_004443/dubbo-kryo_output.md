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
# Warmup Iteration   1: 1.750 ops/ms
Iteration   1: 7.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.215 ops/ms


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
# Warmup Iteration   1: 5.115 ops/ms
Iteration   1: 12.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.227 ops/ms


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
# Warmup Iteration   1: 5.283 ops/ms
Iteration   1: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.669 ops/ms


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
# Warmup Iteration   1: 4.965 ops/ms
Iteration   1: 7.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.640 ops/ms


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.082 ms/op
Iteration   1: 2.240 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.240 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.061 ms/op
Iteration   1: 2.042 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.042 ms/op


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.056 ms/op
Iteration   1: 2.034 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.100 ms/op
Iteration   1: 3.449 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.449 ms/op


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.144 ms/op
Iteration   1: 2.350 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  15.489 ms/op
                 createUser·p0.9999: 23.413 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13602
  mean =      2.350 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10612 
    [ 2.500,  5.000) = 2771 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     15.489 ms/op
     p(99.9900) =     23.413 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 3.033 ±(99.9%) 0.071 ms/op
Iteration   1: 1.770 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.129 ms/op
                 existUser·p0.999:  26.149 ms/op
                 existUser·p0.9999: 28.060 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18075
  mean =      1.770 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17596 
    [ 2.500,  5.000) = 365 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.129 ms/op
     p(99.9000) =     26.149 ms/op
     p(99.9900) =     28.060 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.085 ms/op
Iteration   1: 2.093 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.251 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.851 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  12.239 ms/op
                 getUser·p0.9999: 12.899 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15278
  mean =      2.093 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 313 
    [ 1.250,  2.500) = 11453 
    [ 2.500,  3.750) = 3247 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.251 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     12.899 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.130 ms/op
Iteration   1: 3.521 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.224 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  57.087 ms/op
                 listUser·p0.9999: 64.225 ms/op
                 listUser·p1.00:   64.225 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9083
  mean =      3.521 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8924 
    [ 5.000, 10.000) = 93 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 16 
    [55.000, 60.000) = 12 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     57.087 ms/op
     p(99.9900) =     64.225 ms/op
     p(99.9990) =     64.225 ms/op
     p(99.9999) =     64.225 ms/op
    p(100.0000) =     64.225 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.215          ops/ms
ClientSimple.existUser                       thrpt         12.227          ops/ms
ClientSimple.getUser                         thrpt         10.669          ops/ms
ClientSimple.listUser                        thrpt          7.640          ops/ms
ClientSimple.createUser                       avgt          2.240           ms/op
ClientSimple.existUser                        avgt          2.042           ms/op
ClientSimple.getUser                          avgt          2.034           ms/op
ClientSimple.listUser                         avgt          3.449           ms/op
ClientSimple.createUser                     sample  13602   2.350 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.184           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.489           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.413           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.542           ms/op
ClientSimple.existUser                      sample  18075   1.770 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.635           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.129           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.149           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.060           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.377           ms/op
ClientSimple.getUser                        sample  15278   2.093 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.251           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.121           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.211           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.899           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.960           ms/op
ClientSimple.listUser                       sample   9083   3.521 ± 0.118   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.900           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.224           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.800           ms/op
ClientSimple.listUser:listUser·p0.999       sample         57.087           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         64.225           ms/op
ClientSimple.listUser:listUser·p1.00        sample         64.225           ms/op

Benchmark result is saved to 1717116032284.json
