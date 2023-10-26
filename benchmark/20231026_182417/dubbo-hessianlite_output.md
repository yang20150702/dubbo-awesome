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
# Warmup Iteration   1: 1.213 ops/ms
Iteration   1: 4.369 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.369 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ops/ms
Iteration   1: 10.306 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.306 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.090 ops/ms
Iteration   1: 7.200 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.200 ops/ms


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
# Warmup Iteration   1: 1.065 ops/ms
Iteration   1: 1.588 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.588 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.038 ±(99.9%) 0.213 ms/op
Iteration   1: 4.967 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.967 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ±(99.9%) 0.135 ms/op
Iteration   1: 2.769 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.769 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.105 ±(99.9%) 0.249 ms/op
Iteration   1: 5.071 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.071 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 28.013 ±(99.9%) 0.785 ms/op
Iteration   1: 15.393 ±(99.9%) 0.149 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.393 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.946 ±(99.9%) 0.280 ms/op
Iteration   1: 3.841 ±(99.9%) 0.091 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   2.716 ms/op
                 createUser·p0.90:   7.193 ms/op
                 createUser·p0.95:   9.044 ms/op
                 createUser·p0.99:   15.291 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8471
  mean =      3.841 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1421 
    [ 2.500,  5.000) = 5593 
    [ 5.000,  7.500) = 741 
    [ 7.500, 10.000) = 386 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     15.291 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 6.306 ±(99.9%) 0.193 ms/op
Iteration   1: 2.329 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.226 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  18.884 ms/op
                 existUser·p0.9999: 19.649 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13697
  mean =      2.329 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 345 
    [ 1.250,  2.500) = 11243 
    [ 2.500,  3.750) = 1207 
    [ 3.750,  5.000) = 281 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 180 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.226 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     18.884 ms/op
     p(99.9900) =     19.649 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 8.098 ±(99.9%) 0.260 ms/op
Iteration   1: 3.165 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   10.224 ms/op
                 getUser·p0.999:  16.777 ms/op
                 getUser·p0.9999: 17.596 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10106
  mean =      3.165 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 2793 
    [ 2.500,  3.750) = 5882 
    [ 3.750,  5.000) = 844 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 23.515 ±(99.9%) 0.836 ms/op
Iteration   1: 15.183 ±(99.9%) 0.382 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   13.877 ms/op
                 listUser·p0.90:   21.204 ms/op
                 listUser·p0.95:   25.790 ms/op
                 listUser·p0.99:   34.931 ms/op
                 listUser·p0.999:  38.890 ms/op
                 listUser·p0.9999: 40.174 ms/op
                 listUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2098
  mean =     15.183 ±(99.9%) 0.382 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4 
    [ 5.000, 10.000) = 197 
    [10.000, 15.000) = 1080 
    [15.000, 20.000) = 540 
    [20.000, 25.000) = 163 
    [25.000, 30.000) = 49 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =     13.877 ms/op
     p(90.0000) =     21.204 ms/op
     p(95.0000) =     25.790 ms/op
     p(99.0000) =     34.931 ms/op
     p(99.9000) =     38.890 ms/op
     p(99.9900) =     40.174 ms/op
     p(99.9990) =     40.174 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.369          ops/ms
Client.existUser                       thrpt         10.306          ops/ms
Client.getUser                         thrpt          7.200          ops/ms
Client.listUser                        thrpt          1.588          ops/ms
Client.createUser                       avgt          4.967           ms/op
Client.existUser                        avgt          2.769           ms/op
Client.getUser                          avgt          5.071           ms/op
Client.listUser                         avgt         15.393           ms/op
Client.createUser                     sample   8471   3.841 ± 0.091   ms/op
Client.createUser:createUser·p0.00    sample          1.231           ms/op
Client.createUser:createUser·p0.50    sample          2.716           ms/op
Client.createUser:createUser·p0.90    sample          7.193           ms/op
Client.createUser:createUser·p0.95    sample          9.044           ms/op
Client.createUser:createUser·p0.99    sample         15.291           ms/op
Client.createUser:createUser·p0.999   sample         21.463           ms/op
Client.createUser:createUser·p0.9999  sample         24.609           ms/op
Client.createUser:createUser·p1.00    sample         24.609           ms/op
Client.existUser                      sample  13697   2.329 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample          0.226           ms/op
Client.existUser:existUser·p0.50      sample          1.880           ms/op
Client.existUser:existUser·p0.90      sample          2.941           ms/op
Client.existUser:existUser·p0.95      sample          4.825           ms/op
Client.existUser:existUser·p0.99      sample         10.453           ms/op
Client.existUser:existUser·p0.999     sample         18.884           ms/op
Client.existUser:existUser·p0.9999    sample         19.649           ms/op
Client.existUser:existUser·p1.00      sample         19.661           ms/op
Client.getUser                        sample  10106   3.165 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          1.161           ms/op
Client.getUser:getUser·p0.50          sample          2.859           ms/op
Client.getUser:getUser·p0.90          sample          4.055           ms/op
Client.getUser:getUser·p0.95          sample          5.300           ms/op
Client.getUser:getUser·p0.99          sample         10.224           ms/op
Client.getUser:getUser·p0.999         sample         16.777           ms/op
Client.getUser:getUser·p0.9999        sample         17.596           ms/op
Client.getUser:getUser·p1.00          sample         17.596           ms/op
Client.listUser                       sample   2098  15.183 ± 0.382   ms/op
Client.listUser:listUser·p0.00        sample          1.935           ms/op
Client.listUser:listUser·p0.50        sample         13.877           ms/op
Client.listUser:listUser·p0.90        sample         21.204           ms/op
Client.listUser:listUser·p0.95        sample         25.790           ms/op
Client.listUser:listUser·p0.99        sample         34.931           ms/op
Client.listUser:listUser·p0.999       sample         38.890           ms/op
Client.listUser:listUser·p0.9999      sample         40.174           ms/op
Client.listUser:listUser·p1.00        sample         40.174           ms/op
