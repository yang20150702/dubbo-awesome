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
# Warmup Iteration   1: 2.494 ops/ms
Iteration   1: 6.738 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.738 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.387 ops/ms
Iteration   1: 13.359 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.359 ops/ms


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
# Warmup Iteration   1: 4.188 ops/ms
Iteration   1: 7.787 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.787 ops/ms


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
# Warmup Iteration   1: 2.162 ops/ms
Iteration   1: 3.657 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.657 ops/ms


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
# Warmup Iteration   1: 4.983 ±(99.9%) 0.077 ms/op
Iteration   1: 3.068 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.068 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.049 ms/op
Iteration   1: 1.823 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.064 ms/op
Iteration   1: 2.791 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.791 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.758 ±(99.9%) 0.214 ms/op
Iteration   1: 7.866 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.866 ms/op


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
# Warmup Iteration   1: 4.830 ±(99.9%) 0.091 ms/op
Iteration   1: 3.253 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.991 ms/op
                 createUser·p0.95:   4.331 ms/op
                 createUser·p0.99:   7.955 ms/op
                 createUser·p0.999:  18.127 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9865
  mean =      3.253 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1278 
    [ 2.500,  3.750) = 7036 
    [ 3.750,  5.000) = 1328 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.991 ms/op
     p(95.0000) =      4.331 ms/op
     p(99.0000) =      7.955 ms/op
     p(99.9000) =     18.127 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 2.823 ±(99.9%) 0.057 ms/op
Iteration   1: 1.803 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17710
  mean =      1.803 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 536 
    [ 1.250,  2.500) = 16445 
    [ 2.500,  3.750) = 549 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.102 ms/op
Iteration   1: 3.014 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.847 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   9.275 ms/op
                 getUser·p0.999:  14.662 ms/op
                 getUser·p0.9999: 15.914 ms/op
                 getUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10698
  mean =      3.014 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 3188 
    [ 2.500,  3.750) = 6352 
    [ 3.750,  5.000) = 804 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      9.275 ms/op
     p(99.9000) =     14.662 ms/op
     p(99.9900) =     15.914 ms/op
     p(99.9990) =     15.925 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 10.856 ±(99.9%) 0.317 ms/op
Iteration   1: 7.239 ±(99.9%) 0.097 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   6.963 ms/op
                 listUser·p0.90:   9.535 ms/op
                 listUser·p0.95:   10.551 ms/op
                 listUser·p0.99:   15.234 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4429
  mean =      7.239 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 314 
    [ 5.000,  7.500) = 2559 
    [ 7.500, 10.000) = 1223 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      6.963 ms/op
     p(90.0000) =      9.535 ms/op
     p(95.0000) =     10.551 ms/op
     p(99.0000) =     15.234 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.738          ops/ms
Client.existUser                       thrpt         13.359          ops/ms
Client.getUser                         thrpt          7.787          ops/ms
Client.listUser                        thrpt          3.657          ops/ms
Client.createUser                       avgt          3.068           ms/op
Client.existUser                        avgt          1.823           ms/op
Client.getUser                          avgt          2.791           ms/op
Client.listUser                         avgt          7.866           ms/op
Client.createUser                     sample   9865   3.253 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.063           ms/op
Client.createUser:createUser·p0.50    sample          3.068           ms/op
Client.createUser:createUser·p0.90    sample          3.991           ms/op
Client.createUser:createUser·p0.95    sample          4.331           ms/op
Client.createUser:createUser·p0.99    sample          7.955           ms/op
Client.createUser:createUser·p0.999   sample         18.127           ms/op
Client.createUser:createUser·p0.9999  sample         19.235           ms/op
Client.createUser:createUser·p1.00    sample         19.235           ms/op
Client.existUser                      sample  17710   1.803 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.714           ms/op
Client.existUser:existUser·p0.50      sample          1.667           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.441           ms/op
Client.existUser:existUser·p0.99      sample          3.772           ms/op
Client.existUser:existUser·p0.999     sample         11.256           ms/op
Client.existUser:existUser·p0.9999    sample         11.567           ms/op
Client.existUser:existUser·p1.00      sample         11.567           ms/op
Client.getUser                        sample  10698   3.014 ± 0.039   ms/op
Client.getUser:getUser·p0.00          sample          0.830           ms/op
Client.getUser:getUser·p0.50          sample          2.847           ms/op
Client.getUser:getUser·p0.90          sample          3.785           ms/op
Client.getUser:getUser·p0.95          sample          4.268           ms/op
Client.getUser:getUser·p0.99          sample          9.275           ms/op
Client.getUser:getUser·p0.999         sample         14.662           ms/op
Client.getUser:getUser·p0.9999        sample         15.914           ms/op
Client.getUser:getUser·p1.00          sample         15.925           ms/op
Client.listUser                       sample   4429   7.239 ± 0.097   ms/op
Client.listUser:listUser·p0.00        sample          1.403           ms/op
Client.listUser:listUser·p0.50        sample          6.963           ms/op
Client.listUser:listUser·p0.90        sample          9.535           ms/op
Client.listUser:listUser·p0.95        sample         10.551           ms/op
Client.listUser:listUser·p0.99        sample         15.234           ms/op
Client.listUser:listUser·p0.999       sample         19.104           ms/op
Client.listUser:listUser·p0.9999      sample         21.332           ms/op
Client.listUser:listUser·p1.00        sample         21.332           ms/op
