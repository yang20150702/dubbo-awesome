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
# Warmup Iteration   1: 1.051 ops/ms
Iteration   1: 2.380 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.380 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:29
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ops/ms
Iteration   1: 6.837 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.837 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.868 ops/ms
Iteration   1: 3.339 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.339 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.905 ops/ms
Iteration   1: 1.318 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.318 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 13.009 ±(99.9%) 0.245 ms/op
Iteration   1: 7.789 ±(99.9%) 0.146 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.789 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 9.441 ±(99.9%) 0.133 ms/op
Iteration   1: 4.209 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.209 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.007 ±(99.9%) 0.309 ms/op
Iteration   1: 5.202 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.202 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 32.183 ±(99.9%) 0.884 ms/op
Iteration   1: 23.280 ±(99.9%) 0.303 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.280 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.695 ±(99.9%) 0.396 ms/op
Iteration   1: 6.210 ±(99.9%) 0.187 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   10.043 ms/op
                 createUser·p0.95:   14.434 ms/op
                 createUser·p0.99:   21.627 ms/op
                 createUser·p0.999:  37.345 ms/op
                 createUser·p0.9999: 43.450 ms/op
                 createUser·p1.00:   43.450 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5125
  mean =      6.210 ±(99.9%) 0.187 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2905 
    [ 5.000, 10.000) = 1706 
    [10.000, 15.000) = 288 
    [15.000, 20.000) = 155 
    [20.000, 25.000) = 39 
    [25.000, 30.000) = 10 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =     10.043 ms/op
     p(95.0000) =     14.434 ms/op
     p(99.0000) =     21.627 ms/op
     p(99.9000) =     37.345 ms/op
     p(99.9900) =     43.450 ms/op
     p(99.9990) =     43.450 ms/op
     p(99.9999) =     43.450 ms/op
    p(100.0000) =     43.450 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.307 ±(99.9%) 0.232 ms/op
Iteration   1: 3.513 ±(99.9%) 0.127 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   9.191 ms/op
                 existUser·p0.99:   19.036 ms/op
                 existUser·p0.999:  50.463 ms/op
                 existUser·p0.9999: 78.512 ms/op
                 existUser·p1.00:   78.512 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9053
  mean =      3.513 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8045 
    [ 5.000, 10.000) = 706 
    [10.000, 15.000) = 197 
    [15.000, 20.000) = 25 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 12 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     19.036 ms/op
     p(99.9000) =     50.463 ms/op
     p(99.9900) =     78.512 ms/op
     p(99.9990) =     78.512 ms/op
     p(99.9999) =     78.512 ms/op
    p(100.0000) =     78.512 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:16
# Fork: 1 of 1
# Warmup Iteration   1: 11.028 ±(99.9%) 0.323 ms/op
Iteration   1: 5.251 ±(99.9%) 0.091 ms/op
                 getUser·p0.00:   1.933 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   7.401 ms/op
                 getUser·p0.95:   10.083 ms/op
                 getUser·p0.99:   14.385 ms/op
                 getUser·p0.999:  15.923 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6055
  mean =      5.251 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 12 
    [ 2.500,  3.750) = 942 
    [ 3.750,  5.000) = 2663 
    [ 5.000,  6.250) = 1414 
    [ 6.250,  7.500) = 443 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      7.401 ms/op
     p(95.0000) =     10.083 ms/op
     p(99.0000) =     14.385 ms/op
     p(99.9000) =     15.923 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 31.940 ±(99.9%) 0.980 ms/op
Iteration   1: 19.958 ±(99.9%) 0.463 ms/op
                 listUser·p0.00:   7.348 ms/op
                 listUser·p0.50:   19.071 ms/op
                 listUser·p0.90:   27.355 ms/op
                 listUser·p0.95:   30.304 ms/op
                 listUser·p0.99:   36.686 ms/op
                 listUser·p0.999:  45.613 ms/op
                 listUser·p0.9999: 45.613 ms/op
                 listUser·p1.00:   45.613 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1621
  mean =     19.958 ±(99.9%) 0.463 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 14 
    [10.000, 15.000) = 293 
    [15.000, 20.000) = 601 
    [20.000, 25.000) = 432 
    [25.000, 30.000) = 194 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      7.348 ms/op
     p(50.0000) =     19.071 ms/op
     p(90.0000) =     27.355 ms/op
     p(95.0000) =     30.304 ms/op
     p(99.0000) =     36.686 ms/op
     p(99.9000) =     45.613 ms/op
     p(99.9900) =     45.613 ms/op
     p(99.9990) =     45.613 ms/op
     p(99.9999) =     45.613 ms/op
    p(100.0000) =     45.613 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.380          ops/ms
Client.existUser                       thrpt         6.837          ops/ms
Client.getUser                         thrpt         3.339          ops/ms
Client.listUser                        thrpt         1.318          ops/ms
Client.createUser                       avgt         7.789           ms/op
Client.existUser                        avgt         4.209           ms/op
Client.getUser                          avgt         5.202           ms/op
Client.listUser                         avgt        23.280           ms/op
Client.createUser                     sample  5125   6.210 ± 0.187   ms/op
Client.createUser:createUser·p0.00    sample         0.629           ms/op
Client.createUser:createUser·p0.50    sample         4.424           ms/op
Client.createUser:createUser·p0.90    sample        10.043           ms/op
Client.createUser:createUser·p0.95    sample        14.434           ms/op
Client.createUser:createUser·p0.99    sample        21.627           ms/op
Client.createUser:createUser·p0.999   sample        37.345           ms/op
Client.createUser:createUser·p0.9999  sample        43.450           ms/op
Client.createUser:createUser·p1.00    sample        43.450           ms/op
Client.existUser                      sample  9053   3.513 ± 0.127   ms/op
Client.existUser:existUser·p0.00      sample         1.073           ms/op
Client.existUser:existUser·p0.50      sample         2.568           ms/op
Client.existUser:existUser·p0.90      sample         5.177           ms/op
Client.existUser:existUser·p0.95      sample         9.191           ms/op
Client.existUser:existUser·p0.99      sample        19.036           ms/op
Client.existUser:existUser·p0.999     sample        50.463           ms/op
Client.existUser:existUser·p0.9999    sample        78.512           ms/op
Client.existUser:existUser·p1.00      sample        78.512           ms/op
Client.getUser                        sample  6055   5.251 ± 0.091   ms/op
Client.getUser:getUser·p0.00          sample         1.933           ms/op
Client.getUser:getUser·p0.50          sample         4.637           ms/op
Client.getUser:getUser·p0.90          sample         7.401           ms/op
Client.getUser:getUser·p0.95          sample        10.083           ms/op
Client.getUser:getUser·p0.99          sample        14.385           ms/op
Client.getUser:getUser·p0.999         sample        15.923           ms/op
Client.getUser:getUser·p0.9999        sample        18.776           ms/op
Client.getUser:getUser·p1.00          sample        18.776           ms/op
Client.listUser                       sample  1621  19.958 ± 0.463   ms/op
Client.listUser:listUser·p0.00        sample         7.348           ms/op
Client.listUser:listUser·p0.50        sample        19.071           ms/op
Client.listUser:listUser·p0.90        sample        27.355           ms/op
Client.listUser:listUser·p0.95        sample        30.304           ms/op
Client.listUser:listUser·p0.99        sample        36.686           ms/op
Client.listUser:listUser·p0.999       sample        45.613           ms/op
Client.listUser:listUser·p0.9999      sample        45.613           ms/op
Client.listUser:listUser·p1.00        sample        45.613           ms/op
