# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 4.094 ops/ms
# Warmup Iteration   3: 7.187 ops/ms
Iteration   1: 7.331 ops/ms
Iteration   2: 7.828 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.698 ±(99.9%) 5.872 ops/ms [Average]
  (min, avg, max) = (7.331, 7.698, 7.935), stdev = 0.322
  CI (99.9%): [1.826, 13.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.390 ops/ms
# Warmup Iteration   2: 7.048 ops/ms
# Warmup Iteration   3: 7.914 ops/ms
Iteration   1: 8.538 ops/ms
Iteration   2: 8.549 ops/ms
Iteration   3: 8.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.604 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (8.538, 8.604, 8.724), stdev = 0.104
  CI (99.9%): [6.699, 10.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 7.011 ops/ms
# Warmup Iteration   3: 8.061 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.344 ±(99.9%) 2.655 ops/ms [Average]
  (min, avg, max) = (8.179, 8.344, 8.454), stdev = 0.146
  CI (99.9%): [5.689, 10.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.349 ops/ms
# Warmup Iteration   2: 6.199 ops/ms
# Warmup Iteration   3: 6.575 ops/ms
Iteration   1: 6.996 ops/ms
Iteration   2: 6.991 ops/ms
Iteration   3: 6.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.961 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (6.897, 6.961, 6.996), stdev = 0.056
  CI (99.9%): [5.942, 7.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.970 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.893 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.008 ms/op
Iteration   1: 4.055 ±(99.9%) 0.006 ms/op
Iteration   2: 3.924 ±(99.9%) 0.003 ms/op
Iteration   3: 3.911 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.963 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.911, 3.963, 4.055), stdev = 0.080
  CI (99.9%): [2.503, 5.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.713 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.006 ms/op
Iteration   1: 3.876 ±(99.9%) 0.007 ms/op
Iteration   2: 3.821 ±(99.9%) 0.005 ms/op
Iteration   3: 3.816 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.838 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.816, 3.838, 3.876), stdev = 0.033
  CI (99.9%): [3.229, 4.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.570 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.007 ms/op
Iteration   1: 4.032 ±(99.9%) 0.007 ms/op
Iteration   2: 4.022 ±(99.9%) 0.009 ms/op
Iteration   3: 3.945 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.000 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.945, 4.000, 4.032), stdev = 0.048
  CI (99.9%): [3.132, 4.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.032 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.776 ±(99.9%) 0.006 ms/op
Iteration   1: 4.562 ±(99.9%) 0.013 ms/op
Iteration   2: 4.696 ±(99.9%) 0.009 ms/op
Iteration   3: 4.683 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.647 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.562, 4.647, 4.696), stdev = 0.074
  CI (99.9%): [3.305, 5.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.226 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.020 ms/op
Iteration   1: 4.041 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  11.697 ms/op
                 createUser·p0.9999: 27.859 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 4.043 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  26.307 ms/op
                 createUser·p0.9999: 29.985 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  12.534 ms/op
                 createUser·p0.9999: 33.063 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240208
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 358 
    [ 2.500,  5.000) = 227884 
    [ 5.000,  7.500) = 10710 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     15.586 ms/op
     p(99.9900) =     32.014 ms/op
     p(99.9990) =     33.181 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.306 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.855 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.011 ms/op
Iteration   1: 3.789 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  23.318 ms/op
                 existUser·p0.9999: 33.075 ms/op
                 existUser·p1.00:   34.800 ms/op

Iteration   2: 3.785 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 30.492 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 30.799 ms/op
                 existUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249925
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 280 
    [ 2.500,  5.000) = 240851 
    [ 5.000,  7.500) = 7726 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.437 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     34.505 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.400 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.013 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   8.241 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 25.951 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  24.763 ms/op
                 getUser·p0.9999: 26.863 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  9.683 ms/op
                 getUser·p0.9999: 28.763 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244740
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 133 
    [ 2.500,  5.000) = 234544 
    [ 5.000,  7.500) = 7988 
    [ 7.500, 10.000) = 1535 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 131 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     12.492 ms/op
     p(99.9900) =     28.263 ms/op
     p(99.9990) =     30.066 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.874 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.213 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.715 ±(99.9%) 0.015 ms/op
Iteration   1: 4.482 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  21.641 ms/op
                 listUser·p0.9999: 33.686 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   2: 4.670 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   8.431 ms/op
                 listUser·p0.999:  18.360 ms/op
                 listUser·p0.9999: 22.451 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 4.607 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.195 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209232
  mean =      4.585 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 185244 
    [ 5.000,  7.500) = 19798 
    [ 7.500, 10.000) = 3130 
    [10.000, 12.500) = 514 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.931 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     19.252 ms/op
     p(99.9900) =     32.022 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.698 ± 5.872  ops/ms
ClientPb.existUser                       thrpt       3   8.604 ± 1.905  ops/ms
ClientPb.getUser                         thrpt       3   8.344 ± 2.655  ops/ms
ClientPb.listUser                        thrpt       3   6.961 ± 1.020  ops/ms
ClientPb.createUser                       avgt       3   3.963 ± 1.460   ms/op
ClientPb.existUser                        avgt       3   3.838 ± 0.609   ms/op
ClientPb.getUser                          avgt       3   4.000 ± 0.868   ms/op
ClientPb.listUser                         avgt       3   4.647 ± 1.342   ms/op
ClientPb.createUser                     sample  240208   3.995 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.006           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.586           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.014           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.260           ms/op
ClientPb.existUser                      sample  249925   3.837 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.454           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.694           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.437           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  244740   3.923 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.492           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.263           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  209232   4.585 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.252           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.022           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.341           ms/op
