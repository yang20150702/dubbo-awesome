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
# Warmup Iteration   1: 2.344 ops/ms
Iteration   1: 6.042 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.042 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.849 ops/ms
Iteration   1: 12.231 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.231 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.622 ops/ms
Iteration   1: 9.008 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.008 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
Iteration   1: 3.235 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.235 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.509 ±(99.9%) 0.072 ms/op
Iteration   1: 3.065 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.065 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ±(99.9%) 0.029 ms/op
Iteration   1: 1.803 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.803 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.056 ms/op
Iteration   1: 3.028 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.028 ms/op


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
# Warmup Iteration   1: 12.242 ±(99.9%) 0.158 ms/op
Iteration   1: 8.712 ±(99.9%) 0.114 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.712 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.821 ±(99.9%) 0.313 ms/op
Iteration   1: 3.055 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.851 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.023 ms/op
                 createUser·p0.99:   9.395 ms/op
                 createUser·p0.999:  13.853 ms/op
                 createUser·p0.9999: 15.138 ms/op
                 createUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10455
  mean =      3.055 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1723 
    [ 2.500,  3.750) = 8057 
    [ 3.750,  5.000) = 398 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.023 ms/op
     p(99.0000) =      9.395 ms/op
     p(99.9000) =     13.853 ms/op
     p(99.9900) =     15.138 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.932 ±(99.9%) 0.089 ms/op
Iteration   1: 1.709 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.017 ms/op
                 existUser·p0.95:   2.204 ms/op
                 existUser·p0.99:   2.716 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 13.552 ms/op
                 existUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18697
  mean =      1.709 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 18150 
    [ 2.500,  3.750) = 333 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.017 ms/op
     p(95.0000) =      2.204 ms/op
     p(99.0000) =      2.716 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     13.552 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.089 ms/op
Iteration   1: 3.263 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.494 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 16.368 ms/op
                 getUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9808
  mean =      3.263 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 987 
    [ 2.500,  3.750) = 7151 
    [ 3.750,  5.000) = 1457 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.494 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     16.368 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.857 ±(99.9%) 0.366 ms/op
Iteration   1: 8.765 ±(99.9%) 0.142 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   8.315 ms/op
                 listUser·p0.90:   12.091 ms/op
                 listUser·p0.95:   13.386 ms/op
                 listUser·p0.99:   18.138 ms/op
                 listUser·p0.999:  25.022 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3697
  mean =      8.765 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 72 
    [ 5.000,  7.500) = 1127 
    [ 7.500, 10.000) = 1623 
    [10.000, 12.500) = 571 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.462 ms/op
     p(50.0000) =      8.315 ms/op
     p(90.0000) =     12.091 ms/op
     p(95.0000) =     13.386 ms/op
     p(99.0000) =     18.138 ms/op
     p(99.9000) =     25.022 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.042          ops/ms
Client.existUser                       thrpt         12.231          ops/ms
Client.getUser                         thrpt          9.008          ops/ms
Client.listUser                        thrpt          3.235          ops/ms
Client.createUser                       avgt          3.065           ms/op
Client.existUser                        avgt          1.803           ms/op
Client.getUser                          avgt          3.028           ms/op
Client.listUser                         avgt          8.712           ms/op
Client.createUser                     sample  10455   3.055 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.092           ms/op
Client.createUser:createUser·p0.50    sample          2.851           ms/op
Client.createUser:createUser·p0.90    sample          3.576           ms/op
Client.createUser:createUser·p0.95    sample          4.023           ms/op
Client.createUser:createUser·p0.99    sample          9.395           ms/op
Client.createUser:createUser·p0.999   sample         13.853           ms/op
Client.createUser:createUser·p0.9999  sample         15.138           ms/op
Client.createUser:createUser·p1.00    sample         15.139           ms/op
Client.existUser                      sample  18697   1.709 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.655           ms/op
Client.existUser:existUser·p0.50      sample          1.628           ms/op
Client.existUser:existUser·p0.90      sample          2.017           ms/op
Client.existUser:existUser·p0.95      sample          2.204           ms/op
Client.existUser:existUser·p0.99      sample          2.716           ms/op
Client.existUser:existUser·p0.999     sample         12.796           ms/op
Client.existUser:existUser·p0.9999    sample         13.552           ms/op
Client.existUser:existUser·p1.00      sample         13.566           ms/op
Client.getUser                        sample   9808   3.263 ± 0.039   ms/op
Client.getUser:getUser·p0.00          sample          0.697           ms/op
Client.getUser:getUser·p0.50          sample          3.101           ms/op
Client.getUser:getUser·p0.90          sample          3.990           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          6.494           ms/op
Client.getUser:getUser·p0.999         sample         15.270           ms/op
Client.getUser:getUser·p0.9999        sample         16.368           ms/op
Client.getUser:getUser·p1.00          sample         16.368           ms/op
Client.listUser                       sample   3697   8.765 ± 0.142   ms/op
Client.listUser:listUser·p0.00        sample          2.462           ms/op
Client.listUser:listUser·p0.50        sample          8.315           ms/op
Client.listUser:listUser·p0.90        sample         12.091           ms/op
Client.listUser:listUser·p0.95        sample         13.386           ms/op
Client.listUser:listUser·p0.99        sample         18.138           ms/op
Client.listUser:listUser·p0.999       sample         25.022           ms/op
Client.listUser:listUser·p0.9999      sample         25.985           ms/op
Client.listUser:listUser·p1.00        sample         25.985           ms/op
