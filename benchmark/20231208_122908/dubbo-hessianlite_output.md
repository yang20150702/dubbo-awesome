# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.306 ops/ms
Iteration   1: 5.687 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.687 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ops/ms
Iteration   1: 12.638 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.638 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
Iteration   1: 7.586 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.586 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.872 ops/ms
Iteration   1: 3.148 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.148 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.103 ±(99.9%) 0.088 ms/op
Iteration   1: 3.254 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ±(99.9%) 0.046 ms/op
Iteration   1: 1.949 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.949 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.813 ±(99.9%) 0.052 ms/op
Iteration   1: 3.255 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.255 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.002 ±(99.9%) 0.151 ms/op
Iteration   1: 8.638 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ±(99.9%) 0.157 ms/op
Iteration   1: 3.729 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   12.914 ms/op
                 createUser·p0.999:  18.553 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8559
  mean =      3.729 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 590 
    [ 2.500,  5.000) = 7182 
    [ 5.000,  7.500) = 558 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =     12.914 ms/op
     p(99.9000) =     18.553 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.242 ±(99.9%) 0.132 ms/op
Iteration   1: 1.768 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.248 ms/op
                 existUser·p0.999:  25.068 ms/op
                 existUser·p0.9999: 25.786 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18457
  mean =      1.768 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17705 
    [ 2.500,  5.000) = 682 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.248 ms/op
     p(99.9000) =     25.068 ms/op
     p(99.9900) =     25.786 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 5.166 ±(99.9%) 0.137 ms/op
Iteration   1: 3.345 ±(99.9%) 0.118 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   9.804 ms/op
                 getUser·p0.999:  66.052 ms/op
                 getUser·p0.9999: 75.497 ms/op
                 getUser·p1.00:   75.497 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9561
  mean =      3.345 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9235 
    [ 5.000, 10.000) = 242 
    [10.000, 15.000) = 38 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 8 
    [70.000, 75.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      9.804 ms/op
     p(99.9000) =     66.052 ms/op
     p(99.9900) =     75.497 ms/op
     p(99.9990) =     75.497 ms/op
     p(99.9999) =     75.497 ms/op
    p(100.0000) =     75.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.359 ±(99.9%) 0.486 ms/op
Iteration   1: 8.202 ±(99.9%) 0.108 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   7.954 ms/op
                 listUser·p0.90:   10.573 ms/op
                 listUser·p0.95:   11.561 ms/op
                 listUser·p0.99:   14.418 ms/op
                 listUser·p0.999:  23.022 ms/op
                 listUser·p0.9999: 24.805 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3946
  mean =      8.202 ±(99.9%) 0.108 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 102 
    [ 5.000,  7.500) = 1370 
    [ 7.500, 10.000) = 1880 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      7.954 ms/op
     p(90.0000) =     10.573 ms/op
     p(95.0000) =     11.561 ms/op
     p(99.0000) =     14.418 ms/op
     p(99.9000) =     23.022 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.687          ops/ms
Client.existUser                       thrpt         12.638          ops/ms
Client.getUser                         thrpt          7.586          ops/ms
Client.listUser                        thrpt          3.148          ops/ms
Client.createUser                       avgt          3.254           ms/op
Client.existUser                        avgt          1.949           ms/op
Client.getUser                          avgt          3.255           ms/op
Client.listUser                         avgt          8.638           ms/op
Client.createUser                     sample   8559   3.729 ± 0.059   ms/op
Client.createUser:createUser·p0.00    sample          0.513           ms/op
Client.createUser:createUser·p0.50    sample          3.375           ms/op
Client.createUser:createUser·p0.90    sample          4.907           ms/op
Client.createUser:createUser·p0.95    sample          5.898           ms/op
Client.createUser:createUser·p0.99    sample         12.914           ms/op
Client.createUser:createUser·p0.999   sample         18.553           ms/op
Client.createUser:createUser·p0.9999  sample         20.546           ms/op
Client.createUser:createUser·p1.00    sample         20.546           ms/op
Client.existUser                      sample  18457   1.768 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.645           ms/op
Client.existUser:existUser·p0.50      sample          1.661           ms/op
Client.existUser:existUser·p0.90      sample          2.212           ms/op
Client.existUser:existUser·p0.95      sample          2.437           ms/op
Client.existUser:existUser·p0.99      sample          3.248           ms/op
Client.existUser:existUser·p0.999     sample         25.068           ms/op
Client.existUser:existUser·p0.9999    sample         25.786           ms/op
Client.existUser:existUser·p1.00      sample         25.952           ms/op
Client.getUser                        sample   9561   3.345 ± 0.118   ms/op
Client.getUser:getUser·p0.00          sample          1.255           ms/op
Client.getUser:getUser·p0.50          sample          2.961           ms/op
Client.getUser:getUser·p0.90          sample          3.973           ms/op
Client.getUser:getUser·p0.95          sample          4.579           ms/op
Client.getUser:getUser·p0.99          sample          9.804           ms/op
Client.getUser:getUser·p0.999         sample         66.052           ms/op
Client.getUser:getUser·p0.9999        sample         75.497           ms/op
Client.getUser:getUser·p1.00          sample         75.497           ms/op
Client.listUser                       sample   3946   8.202 ± 0.108   ms/op
Client.listUser:listUser·p0.00        sample          2.126           ms/op
Client.listUser:listUser·p0.50        sample          7.954           ms/op
Client.listUser:listUser·p0.90        sample         10.573           ms/op
Client.listUser:listUser·p0.95        sample         11.561           ms/op
Client.listUser:listUser·p0.99        sample         14.418           ms/op
Client.listUser:listUser·p0.999       sample         23.022           ms/op
Client.listUser:listUser·p0.9999      sample         24.805           ms/op
Client.listUser:listUser·p1.00        sample         24.805           ms/op
