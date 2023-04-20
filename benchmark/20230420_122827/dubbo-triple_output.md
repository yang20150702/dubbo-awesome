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
# Warmup Iteration   1: 1.606 ops/ms
# Warmup Iteration   2: 3.731 ops/ms
# Warmup Iteration   3: 6.860 ops/ms
Iteration   1: 7.435 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 7.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.728 ±(99.9%) 5.186 ops/ms [Average]
  (min, avg, max) = (7.435, 7.728, 8.003), stdev = 0.284
  CI (99.9%): [2.541, 12.914] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 8.184 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.359 ±(99.9%) 4.670 ops/ms [Average]
  (min, avg, max) = (8.184, 8.359, 8.653), stdev = 0.256
  CI (99.9%): [3.688, 13.029] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 5.863 ops/ms
# Warmup Iteration   3: 8.034 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.866 ±(99.9%) 3.034 ops/ms [Average]
  (min, avg, max) = (7.700, 7.866, 8.033), stdev = 0.166
  CI (99.9%): [4.833, 10.900] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.000 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 6.820 ops/ms
Iteration   1: 6.852 ops/ms
Iteration   2: 6.897 ops/ms
Iteration   3: 6.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.749 ±(99.9%) 3.967 ops/ms [Average]
  (min, avg, max) = (6.500, 6.749, 6.897), stdev = 0.217
  CI (99.9%): [2.783, 10.716] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.508 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.006 ms/op
Iteration   1: 4.250 ±(99.9%) 0.006 ms/op
Iteration   2: 4.038 ±(99.9%) 0.008 ms/op
Iteration   3: 4.187 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.158 ±(99.9%) 1.983 ms/op [Average]
  (min, avg, max) = (4.038, 4.158, 4.250), stdev = 0.109
  CI (99.9%): [2.175, 6.141] (assumes normal distribution)


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
# Warmup Iteration   1: 11.576 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.004 ms/op
Iteration   1: 3.916 ±(99.9%) 0.004 ms/op
Iteration   2: 3.816 ±(99.9%) 0.005 ms/op
Iteration   3: 3.834 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.855 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.816, 3.855, 3.916), stdev = 0.053
  CI (99.9%): [2.884, 4.827] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.178 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.155 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.008 ms/op
Iteration   1: 4.081 ±(99.9%) 0.008 ms/op
Iteration   2: 4.075 ±(99.9%) 0.008 ms/op
Iteration   3: 3.851 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.002 ±(99.9%) 2.388 ms/op [Average]
  (min, avg, max) = (3.851, 4.002, 4.081), stdev = 0.131
  CI (99.9%): [1.614, 6.390] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.791 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.419 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.012 ms/op
Iteration   1: 4.559 ±(99.9%) 0.011 ms/op
Iteration   2: 4.676 ±(99.9%) 0.008 ms/op
Iteration   3: 4.683 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.640 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (4.559, 4.640, 4.683), stdev = 0.070
  CI (99.9%): [3.369, 5.910] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.343 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.122 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.019 ms/op
Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  23.691 ms/op
                 createUser·p0.9999: 26.868 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  12.787 ms/op
                 createUser·p0.9999: 28.058 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.930 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  27.971 ms/op
                 createUser·p0.9999: 39.509 ms/op
                 createUser·p1.00:   40.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240618
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 228579 
    [ 5.000, 10.000) = 11404 
    [10.000, 15.000) = 372 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 168 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     40.802 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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
# Warmup Iteration   1: 11.963 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.014 ms/op
Iteration   1: 3.751 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  23.034 ms/op
                 existUser·p0.9999: 25.993 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 3.867 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.898 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 28.443 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.542 ms/op
                 existUser·p0.999:  27.558 ms/op
                 existUser·p0.9999: 30.091 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251643
  mean =      3.816 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191 
    [ 2.500,  5.000) = 244016 
    [ 5.000,  7.500) = 5767 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     22.067 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     30.802 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.186 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.699 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.015 ms/op
Iteration   1: 4.304 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.015 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   6.496 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  18.803 ms/op
                 getUser·p0.9999: 29.278 ms/op
                 getUser·p1.00:   30.802 ms/op

Iteration   2: 3.988 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  25.683 ms/op
                 getUser·p0.9999: 27.523 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 4.241 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.087 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   8.363 ms/op
                 getUser·p0.999:  15.640 ms/op
                 getUser·p0.9999: 31.756 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229782
  mean =      4.173 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 210177 
    [ 5.000,  7.500) = 15533 
    [ 7.500, 10.000) = 2958 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     22.299 ms/op
     p(99.9900) =     29.852 ms/op
     p(99.9990) =     32.234 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 14.180 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.051 ±(99.9%) 0.020 ms/op
Iteration   1: 4.720 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  25.011 ms/op
                 listUser·p0.9999: 29.562 ms/op
                 listUser·p1.00:   30.933 ms/op

Iteration   2: 4.879 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  20.986 ms/op
                 listUser·p0.9999: 23.426 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 4.702 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  18.551 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201212
  mean =      4.766 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 158738 
    [ 5.000,  7.500) = 36829 
    [ 7.500, 10.000) = 4299 
    [10.000, 12.500) = 738 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.388 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     28.275 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.728 ± 5.186  ops/ms
ClientPb.existUser                       thrpt       3   8.359 ± 4.670  ops/ms
ClientPb.getUser                         thrpt       3   7.866 ± 3.034  ops/ms
ClientPb.listUser                        thrpt       3   6.749 ± 3.967  ops/ms
ClientPb.createUser                       avgt       3   4.158 ± 1.983   ms/op
ClientPb.existUser                        avgt       3   3.855 ± 0.972   ms/op
ClientPb.getUser                          avgt       3   4.002 ± 2.388   ms/op
ClientPb.listUser                         avgt       3   4.640 ± 1.271   ms/op
ClientPb.createUser                     sample  240618   3.991 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.691           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.011           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.894           ms/op
ClientPb.existUser                      sample  251643   3.816 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.712           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.840           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.067           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.229           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  229782   4.173 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.438           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.454           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.299           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.852           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  201212   4.766 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.388           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.234           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.275           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.933           ms/op
