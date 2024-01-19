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
# Warmup Iteration   1: 2.239 ops/ms
Iteration   1: 5.736 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.736 ops/ms


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
# Warmup Iteration   1: 6.053 ops/ms
Iteration   1: 12.485 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.485 ops/ms


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
# Warmup Iteration   1: 3.891 ops/ms
Iteration   1: 7.822 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.822 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.281 ops/ms
Iteration   1: 3.965 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.965 ops/ms


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.065 ms/op
Iteration   1: 3.099 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.099 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.037 ms/op
Iteration   1: 2.038 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.038 ms/op


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
# Warmup Iteration   1: 4.702 ±(99.9%) 0.052 ms/op
Iteration   1: 2.956 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.956 ms/op


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
# Warmup Iteration   1: 11.417 ±(99.9%) 0.226 ms/op
Iteration   1: 7.611 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.611 ms/op


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
# Warmup Iteration   1: 5.253 ±(99.9%) 0.131 ms/op
Iteration   1: 3.440 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  13.151 ms/op
                 createUser·p0.9999: 13.271 ms/op
                 createUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9297
  mean =      3.440 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 463 
    [ 2.500,  3.750) = 6513 
    [ 3.750,  5.000) = 2052 
    [ 5.000,  6.250) = 164 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     13.151 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


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
# Warmup Iteration   1: 3.277 ±(99.9%) 0.076 ms/op
Iteration   1: 1.792 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.393 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.018 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 13.348 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17854
  mean =      1.792 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1573 
    [ 1.250,  2.500) = 15259 
    [ 2.500,  3.750) = 905 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 3 
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
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.018 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     13.348 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.092 ms/op
Iteration   1: 3.055 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  6.754 ms/op
                 getUser·p0.9999: 8.496 ms/op
                 getUser·p1.00:   8.536 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10459
  mean =      3.055 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 31 
    [1.500, 2.000) = 142 
    [2.000, 2.500) = 1376 
    [2.500, 3.000) = 3992 
    [3.000, 3.500) = 2744 
    [3.500, 4.000) = 1505 
    [4.000, 4.500) = 410 
    [4.500, 5.000) = 122 
    [5.000, 5.500) = 48 
    [5.500, 6.000) = 16 
    [6.000, 6.500) = 59 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      6.754 ms/op
     p(99.9900) =      8.496 ms/op
     p(99.9990) =      8.536 ms/op
     p(99.9999) =      8.536 ms/op
    p(100.0000) =      8.536 ms/op


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
# Warmup Iteration   1: 11.619 ±(99.9%) 0.466 ms/op
Iteration   1: 7.860 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   7.545 ms/op
                 listUser·p0.90:   9.863 ms/op
                 listUser·p0.95:   10.695 ms/op
                 listUser·p0.99:   14.370 ms/op
                 listUser·p0.999:  24.668 ms/op
                 listUser·p0.9999: 31.162 ms/op
                 listUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4064
  mean =      7.860 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 77 
    [ 5.000,  7.500) = 1905 
    [ 7.500, 10.000) = 1718 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.818 ms/op
     p(50.0000) =      7.545 ms/op
     p(90.0000) =      9.863 ms/op
     p(95.0000) =     10.695 ms/op
     p(99.0000) =     14.370 ms/op
     p(99.9000) =     24.668 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     31.162 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.736          ops/ms
Client.existUser                       thrpt         12.485          ops/ms
Client.getUser                         thrpt          7.822          ops/ms
Client.listUser                        thrpt          3.965          ops/ms
Client.createUser                       avgt          3.099           ms/op
Client.existUser                        avgt          2.038           ms/op
Client.getUser                          avgt          2.956           ms/op
Client.listUser                         avgt          7.611           ms/op
Client.createUser                     sample   9297   3.440 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.378           ms/op
Client.createUser:createUser·p0.50    sample          3.293           ms/op
Client.createUser:createUser·p0.90    sample          4.202           ms/op
Client.createUser:createUser·p0.95    sample          4.604           ms/op
Client.createUser:createUser·p0.99    sample          7.356           ms/op
Client.createUser:createUser·p0.999   sample         13.151           ms/op
Client.createUser:createUser·p0.9999  sample         13.271           ms/op
Client.createUser:createUser·p1.00    sample         13.271           ms/op
Client.existUser                      sample  17854   1.792 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.393           ms/op
Client.existUser:existUser·p0.50      sample          1.700           ms/op
Client.existUser:existUser·p0.90      sample          2.388           ms/op
Client.existUser:existUser·p0.95      sample          2.527           ms/op
Client.existUser:existUser·p0.99      sample          3.018           ms/op
Client.existUser:existUser·p0.999     sample         12.648           ms/op
Client.existUser:existUser·p0.9999    sample         13.348           ms/op
Client.existUser:existUser·p1.00      sample         13.451           ms/op
Client.getUser                        sample  10459   3.055 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.895           ms/op
Client.getUser:getUser·p0.50          sample          2.945           ms/op
Client.getUser:getUser·p0.90          sample          3.842           ms/op
Client.getUser:getUser·p0.95          sample          4.108           ms/op
Client.getUser:getUser·p0.99          sample          5.284           ms/op
Client.getUser:getUser·p0.999         sample          6.754           ms/op
Client.getUser:getUser·p0.9999        sample          8.496           ms/op
Client.getUser:getUser·p1.00          sample          8.536           ms/op
Client.listUser                       sample   4064   7.860 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          2.818           ms/op
Client.listUser:listUser·p0.50        sample          7.545           ms/op
Client.listUser:listUser·p0.90        sample          9.863           ms/op
Client.listUser:listUser·p0.95        sample         10.695           ms/op
Client.listUser:listUser·p0.99        sample         14.370           ms/op
Client.listUser:listUser·p0.999       sample         24.668           ms/op
Client.listUser:listUser·p0.9999      sample         31.162           ms/op
Client.listUser:listUser·p1.00        sample         31.162           ms/op
