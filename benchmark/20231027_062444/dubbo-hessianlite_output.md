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
# Warmup Iteration   1: 1.369 ops/ms
Iteration   1: 3.616 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.616 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
Iteration   1: 9.807 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.807 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.699 ops/ms
Iteration   1: 6.064 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.064 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.013 ops/ms
Iteration   1: 1.791 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.791 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 10.583 ±(99.9%) 0.219 ms/op
Iteration   1: 5.223 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.223 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ±(99.9%) 0.114 ms/op
Iteration   1: 2.628 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.628 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.621 ±(99.9%) 0.345 ms/op
Iteration   1: 4.315 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.315 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 26.354 ±(99.9%) 0.917 ms/op
Iteration   1: 21.948 ±(99.9%) 0.438 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.948 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.018 ±(99.9%) 0.278 ms/op
Iteration   1: 3.572 ±(99.9%) 0.078 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   6.810 ms/op
                 createUser·p0.99:   10.749 ms/op
                 createUser·p0.999:  32.998 ms/op
                 createUser·p0.9999: 33.489 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8992
  mean =      3.572 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 7991 
    [ 5.000,  7.500) = 601 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      6.810 ms/op
     p(99.0000) =     10.749 ms/op
     p(99.9000) =     32.998 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ±(99.9%) 0.157 ms/op
Iteration   1: 2.346 ±(99.9%) 0.046 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 24.921 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13643
  mean =      2.346 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11047 
    [ 2.500,  5.000) = 1980 
    [ 5.000,  7.500) = 253 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     24.921 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.939 ±(99.9%) 0.237 ms/op
Iteration   1: 3.633 ±(99.9%) 0.090 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   6.857 ms/op
                 getUser·p0.99:   19.323 ms/op
                 getUser·p0.999:  25.434 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8830
  mean =      3.633 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 819 
    [ 2.500,  5.000) = 7230 
    [ 5.000,  7.500) = 381 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =     19.323 ms/op
     p(99.9000) =     25.434 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 25.853 ±(99.9%) 0.833 ms/op
Iteration   1: 18.807 ±(99.9%) 0.456 ms/op
                 listUser·p0.00:   5.898 ms/op
                 listUser·p0.50:   17.695 ms/op
                 listUser·p0.90:   26.837 ms/op
                 listUser·p0.95:   29.458 ms/op
                 listUser·p0.99:   38.237 ms/op
                 listUser·p0.999:  44.072 ms/op
                 listUser·p0.9999: 45.416 ms/op
                 listUser·p1.00:   45.416 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1854
  mean =     18.807 ±(99.9%) 0.456 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 51 
    [10.000, 15.000) = 477 
    [15.000, 20.000) = 679 
    [20.000, 25.000) = 361 
    [25.000, 30.000) = 200 
    [30.000, 35.000) = 48 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      5.898 ms/op
     p(50.0000) =     17.695 ms/op
     p(90.0000) =     26.837 ms/op
     p(95.0000) =     29.458 ms/op
     p(99.0000) =     38.237 ms/op
     p(99.9000) =     44.072 ms/op
     p(99.9900) =     45.416 ms/op
     p(99.9990) =     45.416 ms/op
     p(99.9999) =     45.416 ms/op
    p(100.0000) =     45.416 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.616          ops/ms
Client.existUser                       thrpt          9.807          ops/ms
Client.getUser                         thrpt          6.064          ops/ms
Client.listUser                        thrpt          1.791          ops/ms
Client.createUser                       avgt          5.223           ms/op
Client.existUser                        avgt          2.628           ms/op
Client.getUser                          avgt          4.315           ms/op
Client.listUser                         avgt         21.948           ms/op
Client.createUser                     sample   8992   3.572 ± 0.078   ms/op
Client.createUser:createUser·p0.00    sample          1.495           ms/op
Client.createUser:createUser·p0.50    sample          2.920           ms/op
Client.createUser:createUser·p0.90    sample          5.022           ms/op
Client.createUser:createUser·p0.95    sample          6.810           ms/op
Client.createUser:createUser·p0.99    sample         10.749           ms/op
Client.createUser:createUser·p0.999   sample         32.998           ms/op
Client.createUser:createUser·p0.9999  sample         33.489           ms/op
Client.createUser:createUser·p1.00    sample         33.489           ms/op
Client.existUser                      sample  13643   2.346 ± 0.046   ms/op
Client.existUser:existUser·p0.00      sample          0.586           ms/op
Client.existUser:existUser·p0.50      sample          1.913           ms/op
Client.existUser:existUser·p0.90      sample          2.982           ms/op
Client.existUser:existUser·p0.95      sample          4.817           ms/op
Client.existUser:existUser·p0.99      sample         10.322           ms/op
Client.existUser:existUser·p0.999     sample         15.778           ms/op
Client.existUser:existUser·p0.9999    sample         24.921           ms/op
Client.existUser:existUser·p1.00      sample         25.362           ms/op
Client.getUser                        sample   8830   3.633 ± 0.090   ms/op
Client.getUser:getUser·p0.00          sample          1.149           ms/op
Client.getUser:getUser·p0.50          sample          3.047           ms/op
Client.getUser:getUser·p0.90          sample          4.735           ms/op
Client.getUser:getUser·p0.95          sample          6.857           ms/op
Client.getUser:getUser·p0.99          sample         19.323           ms/op
Client.getUser:getUser·p0.999         sample         25.434           ms/op
Client.getUser:getUser·p0.9999        sample         26.608           ms/op
Client.getUser:getUser·p1.00          sample         26.608           ms/op
Client.listUser                       sample   1854  18.807 ± 0.456   ms/op
Client.listUser:listUser·p0.00        sample          5.898           ms/op
Client.listUser:listUser·p0.50        sample         17.695           ms/op
Client.listUser:listUser·p0.90        sample         26.837           ms/op
Client.listUser:listUser·p0.95        sample         29.458           ms/op
Client.listUser:listUser·p0.99        sample         38.237           ms/op
Client.listUser:listUser·p0.999       sample         44.072           ms/op
Client.listUser:listUser·p0.9999      sample         45.416           ms/op
Client.listUser:listUser·p1.00        sample         45.416           ms/op
