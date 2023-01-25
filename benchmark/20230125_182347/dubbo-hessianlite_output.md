# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.011 ops/ms
Iteration   1: 2.825 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.825 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.550 ops/ms
Iteration   1: 8.555 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.555 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.475 ops/ms
Iteration   1: 5.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.020 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.848 ops/ms
Iteration   1: 1.420 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.420 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 17.928 ±(99.9%) 0.284 ms/op
Iteration   1: 7.140 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.140 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.812 ±(99.9%) 0.062 ms/op
Iteration   1: 4.180 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.229 ±(99.9%) 0.120 ms/op
Iteration   1: 4.757 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 25.862 ±(99.9%) 0.330 ms/op
Iteration   1: 15.256 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.256 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.330 ms/op
Iteration   1: 6.457 ±(99.9%) 0.104 ms/op
                 createUser·p0.00:   2.740 ms/op
                 createUser·p0.50:   6.595 ms/op
                 createUser·p0.90:   7.253 ms/op
                 createUser·p0.95:   7.733 ms/op
                 createUser·p0.99:   18.096 ms/op
                 createUser·p0.999:  27.591 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4975
  mean =      6.457 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1013 
    [ 5.000,  7.500) = 3661 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.740 ms/op
     p(50.0000) =      6.595 ms/op
     p(90.0000) =      7.253 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     18.096 ms/op
     p(99.9000) =     27.591 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     27.754 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.835 ±(99.9%) 0.249 ms/op
Iteration   1: 3.271 ±(99.9%) 0.057 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.787 ms/op
                 existUser·p0.99:   11.829 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9778
  mean =      3.271 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 1879 
    [ 2.500,  3.750) = 7109 
    [ 3.750,  5.000) = 242 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.787 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.052 ±(99.9%) 0.274 ms/op
Iteration   1: 3.901 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.640 ms/op
                 getUser·p0.95:   5.326 ms/op
                 getUser·p0.99:   11.519 ms/op
                 getUser·p0.999:  16.967 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8195
  mean =      3.901 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 267 
    [ 2.500,  3.750) = 4326 
    [ 3.750,  5.000) = 3108 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.640 ms/op
     p(95.0000) =      5.326 ms/op
     p(99.0000) =     11.519 ms/op
     p(99.9000) =     16.967 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.521 ±(99.9%) 0.791 ms/op
Iteration   1: 16.428 ±(99.9%) 0.234 ms/op
                 listUser·p0.00:   7.799 ms/op
                 listUser·p0.50:   16.531 ms/op
                 listUser·p0.90:   18.645 ms/op
                 listUser·p0.95:   19.694 ms/op
                 listUser·p0.99:   30.101 ms/op
                 listUser·p0.999:  37.375 ms/op
                 listUser·p0.9999: 37.683 ms/op
                 listUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1939
  mean =     16.428 ±(99.9%) 0.234 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 421 
    [15.000, 17.500) = 956 
    [17.500, 20.000) = 364 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      7.799 ms/op
     p(50.0000) =     16.531 ms/op
     p(90.0000) =     18.645 ms/op
     p(95.0000) =     19.694 ms/op
     p(99.0000) =     30.101 ms/op
     p(99.9000) =     37.375 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     37.683 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.825          ops/ms
Client.existUser                       thrpt         8.555          ops/ms
Client.getUser                         thrpt         5.020          ops/ms
Client.listUser                        thrpt         1.420          ops/ms
Client.createUser                       avgt         7.140           ms/op
Client.existUser                        avgt         4.180           ms/op
Client.getUser                          avgt         4.757           ms/op
Client.listUser                         avgt        15.256           ms/op
Client.createUser                     sample  4975   6.457 ± 0.104   ms/op
Client.createUser:createUser·p0.00    sample         2.740           ms/op
Client.createUser:createUser·p0.50    sample         6.595           ms/op
Client.createUser:createUser·p0.90    sample         7.253           ms/op
Client.createUser:createUser·p0.95    sample         7.733           ms/op
Client.createUser:createUser·p0.99    sample        18.096           ms/op
Client.createUser:createUser·p0.999   sample        27.591           ms/op
Client.createUser:createUser·p0.9999  sample        27.754           ms/op
Client.createUser:createUser·p1.00    sample        27.754           ms/op
Client.existUser                      sample  9778   3.271 ± 0.057   ms/op
Client.existUser:existUser·p0.00      sample         0.815           ms/op
Client.existUser:existUser·p0.50      sample         3.162           ms/op
Client.existUser:existUser·p0.90      sample         3.613           ms/op
Client.existUser:existUser·p0.95      sample         4.787           ms/op
Client.existUser:existUser·p0.99      sample        11.829           ms/op
Client.existUser:existUser·p0.999     sample        19.497           ms/op
Client.existUser:existUser·p0.9999    sample        19.857           ms/op
Client.existUser:existUser·p1.00      sample        19.857           ms/op
Client.getUser                        sample  8195   3.901 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample         1.378           ms/op
Client.getUser:getUser·p0.50          sample         3.674           ms/op
Client.getUser:getUser·p0.90          sample         4.640           ms/op
Client.getUser:getUser·p0.95          sample         5.326           ms/op
Client.getUser:getUser·p0.99          sample        11.519           ms/op
Client.getUser:getUser·p0.999         sample        16.967           ms/op
Client.getUser:getUser·p0.9999        sample        19.464           ms/op
Client.getUser:getUser·p1.00          sample        19.464           ms/op
Client.listUser                       sample  1939  16.428 ± 0.234   ms/op
Client.listUser:listUser·p0.00        sample         7.799           ms/op
Client.listUser:listUser·p0.50        sample        16.531           ms/op
Client.listUser:listUser·p0.90        sample        18.645           ms/op
Client.listUser:listUser·p0.95        sample        19.694           ms/op
Client.listUser:listUser·p0.99        sample        30.101           ms/op
Client.listUser:listUser·p0.999       sample        37.375           ms/op
Client.listUser:listUser·p0.9999      sample        37.683           ms/op
Client.listUser:listUser·p1.00        sample        37.683           ms/op
