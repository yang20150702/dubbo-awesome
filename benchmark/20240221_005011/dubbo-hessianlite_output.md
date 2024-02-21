# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 6.408 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.408 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ops/ms
Iteration   1: 14.247 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.247 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ops/ms
Iteration   1: 9.319 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.319 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.993 ops/ms
Iteration   1: 3.499 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.499 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.829 ±(99.9%) 0.080 ms/op
Iteration   1: 3.192 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.192 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.240 ±(99.9%) 0.043 ms/op
Iteration   1: 1.935 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.054 ms/op
Iteration   1: 3.324 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 15.181 ±(99.9%) 0.232 ms/op
Iteration   1: 8.779 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.779 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.267 ±(99.9%) 0.141 ms/op
Iteration   1: 3.186 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.295 ms/op
                 createUser·p0.99:   9.079 ms/op
                 createUser·p0.999:  14.805 ms/op
                 createUser·p0.9999: 17.853 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10273
  mean =      3.186 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1180 
    [ 2.500,  3.750) = 7470 
    [ 3.750,  5.000) = 1335 
    [ 5.000,  6.250) = 137 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.295 ms/op
     p(99.0000) =      9.079 ms/op
     p(99.9000) =     14.805 ms/op
     p(99.9900) =     17.853 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.524 ±(99.9%) 0.128 ms/op
Iteration   1: 2.102 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.048 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.721 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.488 ms/op
                 existUser·p0.9999: 6.565 ms/op
                 existUser·p1.00:   6.578 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15232
  mean =      2.102 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 23 
    [1.000, 1.500) = 843 
    [1.500, 2.000) = 6056 
    [2.000, 2.500) = 6438 
    [2.500, 3.000) = 1487 
    [3.000, 3.500) = 160 
    [3.500, 4.000) = 57 
    [4.000, 4.500) = 59 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 10 
    [5.500, 6.000) = 49 
    [6.000, 6.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.721 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.488 ms/op
     p(99.9900) =      6.565 ms/op
     p(99.9990) =      6.578 ms/op
     p(99.9999) =      6.578 ms/op
    p(100.0000) =      6.578 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ±(99.9%) 0.114 ms/op
Iteration   1: 3.032 ±(99.9%) 0.227 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  130.739 ms/op
                 getUser·p0.9999: 133.017 ms/op
                 getUser·p1.00:   133.038 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10542
  mean =      3.032 ±(99.9%) 0.227 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 10510 
    [ 12.500,  25.000) = 0 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 32 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =    130.739 ms/op
     p(99.9900) =    133.017 ms/op
     p(99.9990) =    133.038 ms/op
     p(99.9999) =    133.038 ms/op
    p(100.0000) =    133.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.755 ±(99.9%) 0.436 ms/op
Iteration   1: 8.564 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   3.174 ms/op
                 listUser·p0.50:   8.176 ms/op
                 listUser·p0.90:   11.289 ms/op
                 listUser·p0.95:   12.536 ms/op
                 listUser·p0.99:   17.625 ms/op
                 listUser·p0.999:  22.003 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3756
  mean =      8.564 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 57 
    [ 5.000,  7.500) = 1244 
    [ 7.500, 10.000) = 1690 
    [10.000, 12.500) = 576 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.174 ms/op
     p(50.0000) =      8.176 ms/op
     p(90.0000) =     11.289 ms/op
     p(95.0000) =     12.536 ms/op
     p(99.0000) =     17.625 ms/op
     p(99.9000) =     22.003 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           6.408          ops/ms
Client.existUser                       thrpt          14.247          ops/ms
Client.getUser                         thrpt           9.319          ops/ms
Client.listUser                        thrpt           3.499          ops/ms
Client.createUser                       avgt           3.192           ms/op
Client.existUser                        avgt           1.935           ms/op
Client.getUser                          avgt           3.324           ms/op
Client.listUser                         avgt           8.779           ms/op
Client.createUser                     sample  10273    3.186 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample           1.169           ms/op
Client.createUser:createUser·p0.50    sample           2.900           ms/op
Client.createUser:createUser·p0.90    sample           4.010           ms/op
Client.createUser:createUser·p0.95    sample           4.295           ms/op
Client.createUser:createUser·p0.99    sample           9.079           ms/op
Client.createUser:createUser·p0.999   sample          14.805           ms/op
Client.createUser:createUser·p0.9999  sample          17.853           ms/op
Client.createUser:createUser·p1.00    sample          17.859           ms/op
Client.existUser                      sample  15232    2.102 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample           0.825           ms/op
Client.existUser:existUser·p0.50      sample           2.048           ms/op
Client.existUser:existUser·p0.90      sample           2.556           ms/op
Client.existUser:existUser·p0.95      sample           2.721           ms/op
Client.existUser:existUser·p0.99      sample           4.092           ms/op
Client.existUser:existUser·p0.999     sample           6.488           ms/op
Client.existUser:existUser·p0.9999    sample           6.565           ms/op
Client.existUser:existUser·p1.00      sample           6.578           ms/op
Client.getUser                        sample  10542    3.032 ± 0.227   ms/op
Client.getUser:getUser·p0.00          sample           0.833           ms/op
Client.getUser:getUser·p0.50          sample           2.499           ms/op
Client.getUser:getUser·p0.90          sample           3.441           ms/op
Client.getUser:getUser·p0.95          sample           3.760           ms/op
Client.getUser:getUser·p0.99          sample           5.341           ms/op
Client.getUser:getUser·p0.999         sample         130.739           ms/op
Client.getUser:getUser·p0.9999        sample         133.017           ms/op
Client.getUser:getUser·p1.00          sample         133.038           ms/op
Client.listUser                       sample   3756    8.564 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample           3.174           ms/op
Client.listUser:listUser·p0.50        sample           8.176           ms/op
Client.listUser:listUser·p0.90        sample          11.289           ms/op
Client.listUser:listUser·p0.95        sample          12.536           ms/op
Client.listUser:listUser·p0.99        sample          17.625           ms/op
Client.listUser:listUser·p0.999       sample          22.003           ms/op
Client.listUser:listUser·p0.9999      sample          23.298           ms/op
Client.listUser:listUser·p1.00        sample          23.298           ms/op
