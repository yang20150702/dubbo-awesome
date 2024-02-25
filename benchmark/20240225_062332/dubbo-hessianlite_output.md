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
# Warmup Iteration   1: 2.524 ops/ms
Iteration   1: 5.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.344 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.029 ops/ms
Iteration   1: 13.521 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.521 ops/ms


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
# Warmup Iteration   1: 2.843 ops/ms
Iteration   1: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.226 ops/ms


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
# Warmup Iteration   1: 2.026 ops/ms
Iteration   1: 3.879 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.879 ops/ms


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
# Warmup Iteration   1: 5.524 ±(99.9%) 0.072 ms/op
Iteration   1: 3.224 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.224 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.029 ms/op
Iteration   1: 1.989 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.989 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.058 ms/op
Iteration   1: 2.899 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.899 ms/op


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
# Warmup Iteration   1: 11.195 ±(99.9%) 0.166 ms/op
Iteration   1: 9.209 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.209 ms/op


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
# Warmup Iteration   1: 4.904 ±(99.9%) 0.115 ms/op
Iteration   1: 2.831 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.907 ms/op
                 createUser·p0.99:   8.085 ms/op
                 createUser·p0.999:  18.648 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11300
  mean =      2.831 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 4176 
    [ 2.500,  3.750) = 6444 
    [ 3.750,  5.000) = 461 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.907 ms/op
     p(99.0000) =      8.085 ms/op
     p(99.9000) =     18.648 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 2.819 ±(99.9%) 0.058 ms/op
Iteration   1: 2.091 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.222 ms/op
                 existUser·p0.50:   2.095 ms/op
                 existUser·p0.90:   2.810 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   4.277 ms/op
                 existUser·p0.999:  6.379 ms/op
                 existUser·p0.9999: 7.656 ms/op
                 existUser·p1.00:   7.717 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15287
  mean =      2.091 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 17 
    [0.500, 1.000) = 395 
    [1.000, 1.500) = 2068 
    [1.500, 2.000) = 4382 
    [2.000, 2.500) = 5194 
    [2.500, 3.000) = 2508 
    [3.000, 3.500) = 445 
    [3.500, 4.000) = 91 
    [4.000, 4.500) = 77 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 44 
    [5.500, 6.000) = 29 
    [6.000, 6.500) = 30 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.222 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      4.277 ms/op
     p(99.9000) =      6.379 ms/op
     p(99.9900) =      7.656 ms/op
     p(99.9990) =      7.717 ms/op
     p(99.9999) =      7.717 ms/op
    p(100.0000) =      7.717 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.086 ms/op
Iteration   1: 2.898 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   2.761 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.787 ms/op
                 getUser·p0.999:  16.086 ms/op
                 getUser·p0.9999: 18.085 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11061
  mean =      2.898 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3991 
    [ 2.500,  3.750) = 5969 
    [ 3.750,  5.000) = 1020 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.787 ms/op
     p(99.9000) =     16.086 ms/op
     p(99.9900) =     18.085 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.237 ±(99.9%) 0.414 ms/op
Iteration   1: 8.551 ±(99.9%) 0.140 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   8.126 ms/op
                 listUser·p0.90:   11.536 ms/op
                 listUser·p0.95:   12.928 ms/op
                 listUser·p0.99:   18.219 ms/op
                 listUser·p0.999:  20.432 ms/op
                 listUser·p0.9999: 25.756 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3738
  mean =      8.551 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 99 
    [ 5.000,  7.500) = 1347 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 618 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      8.126 ms/op
     p(90.0000) =     11.536 ms/op
     p(95.0000) =     12.928 ms/op
     p(99.0000) =     18.219 ms/op
     p(99.9000) =     20.432 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.344          ops/ms
Client.existUser                       thrpt         13.521          ops/ms
Client.getUser                         thrpt          8.226          ops/ms
Client.listUser                        thrpt          3.879          ops/ms
Client.createUser                       avgt          3.224           ms/op
Client.existUser                        avgt          1.989           ms/op
Client.getUser                          avgt          2.899           ms/op
Client.listUser                         avgt          9.209           ms/op
Client.createUser                     sample  11300   2.831 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.044           ms/op
Client.createUser:createUser·p0.50    sample          2.650           ms/op
Client.createUser:createUser·p0.90    sample          3.375           ms/op
Client.createUser:createUser·p0.95    sample          3.907           ms/op
Client.createUser:createUser·p0.99    sample          8.085           ms/op
Client.createUser:createUser·p0.999   sample         18.648           ms/op
Client.createUser:createUser·p0.9999  sample         18.842           ms/op
Client.createUser:createUser·p1.00    sample         18.842           ms/op
Client.existUser                      sample  15287   2.091 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.222           ms/op
Client.existUser:existUser·p0.50      sample          2.095           ms/op
Client.existUser:existUser·p0.90      sample          2.810           ms/op
Client.existUser:existUser·p0.95      sample          2.986           ms/op
Client.existUser:existUser·p0.99      sample          4.277           ms/op
Client.existUser:existUser·p0.999     sample          6.379           ms/op
Client.existUser:existUser·p0.9999    sample          7.656           ms/op
Client.existUser:existUser·p1.00      sample          7.717           ms/op
Client.getUser                        sample  11061   2.898 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          1.085           ms/op
Client.getUser:getUser·p0.50          sample          2.761           ms/op
Client.getUser:getUser·p0.90          sample          3.744           ms/op
Client.getUser:getUser·p0.95          sample          3.998           ms/op
Client.getUser:getUser·p0.99          sample          4.787           ms/op
Client.getUser:getUser·p0.999         sample         16.086           ms/op
Client.getUser:getUser·p0.9999        sample         18.085           ms/op
Client.getUser:getUser·p1.00          sample         18.186           ms/op
Client.listUser                       sample   3738   8.551 ± 0.140   ms/op
Client.listUser:listUser·p0.00        sample          1.288           ms/op
Client.listUser:listUser·p0.50        sample          8.126           ms/op
Client.listUser:listUser·p0.90        sample         11.536           ms/op
Client.listUser:listUser·p0.95        sample         12.928           ms/op
Client.listUser:listUser·p0.99        sample         18.219           ms/op
Client.listUser:listUser·p0.999       sample         20.432           ms/op
Client.listUser:listUser·p0.9999      sample         25.756           ms/op
Client.listUser:listUser·p1.00        sample         25.756           ms/op
